# React components

- Each React component file must have only one React component.
- All logic inside this file must relate to pure UI manipulation.
- Business logic that can be represented with simple Typescript functions (no React involved) will go to the [use cases](/files/use-cases.md) file.
- If the logic needed to be done requires React interaction (i.e: handling state, calling React-based libraries, API fetching with libraries like react-query, etc) will be implemented as hooks and will go to the "hooks.ts" file of the current folder. Refer to the [hooks](/files/hooks.md) doc for more information
