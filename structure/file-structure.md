# File structure

This document describes the rules to follow hen it comes to organize files on my frontend projects.

- Non React files will follow kebab case convention
- React component files will follow pascal case convention
- This is an example of the folder structure that I follow. Take into account that the names surrounded by the "<" and ">" signs represent folders:
    - <main-feature>/
        - <secondary-feature>/
            - SecondaryFeature.tsx
            - SecondaryFeature.module.css
            - utils.ts
            - use-cases.ts
            - constants.ts
            - types.ts
            - hooks.ts
        - MainFeature.tsx
        - MainFeature.module.css
        - utils.ts
        - use-cases.ts
        - constants.ts
        - types.ts
        - hooks.ts
- Each feature folder will contain at least one file that will be the React component that represents the feature. It will have the same name as the feature folder, but using pascal case instead of kebap case. For example, the "main-feature" feature will contain a "MainFeature.tsx" file.
- To understand how the React components have to be implemented (in the example, "MainFeature.tsx" and "SecondaryFeature.tsx"), refer to the [React components](/files/react-components.md) document.
- To understand how the utils files have to be implemented (in the example, "utils.ts"), refer to the [utils](/files/utils.md) document.
- To understand how the use case files have to be implemented (in the example, "use-cases.ts"), refer to the [use cases](/files/use-cases.md) document.
- To understand how the constants files have to be implemented (in the example, "constants.ts"), refer to the [constants](/files/constants.md) document.
- To understand how the types files have to be implemented (in the example, "types.ts"), refer to the [types](/files/types.md) document.
- To understand how the hooks files have to be implemented (in the example, "hooks.ts"), refer to the [hooks](/files/hooks.md) document.
- To understand how the CSS files have to be implemented (in the example, "MainFeature.module.css" and "SecondaryFeature.module.css"), refer to the [styles](/files/styles.md) document.