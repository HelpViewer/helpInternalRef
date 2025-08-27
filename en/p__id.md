**Default:** ''

Id of target plugins which should process this event.

On every plugin you can specify switch **eventIdStrict** which ensures event dispatching in these modes:

- **eventIdStrict = true** - **plugin.aliasName** must be equal to **event.id** to pass the event to handler
- **eventIdStrict = false** - **event.id** and **plugin.aliasName** must be defined to not falsy value only
