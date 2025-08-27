**(Map)**

Additional data if sent in uri.

- Part with additional data is located in URI, get parameter **p**. 
- Starts with **@@**.
- Defined in pairs, delimiter is **;**.

E.g.: **?p=features.md@@KW;features** will provide highlighting of word **features** in the given chapter text.

This behavior can be extended for your custom logic if wanted.
