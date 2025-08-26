**Default:** ''

Id of target plugins which should process this event.

On every plugin you can specify switch **strictSwitch** which ensures event dispatching in these modes:

- **strictSwitch = true** - **plugin.aliasName** must be equal to **event.id** to pass the event to handler
- **strictSwitch = false** - **event.id** and **plugin.aliasName** must be defined to not falsy value only
