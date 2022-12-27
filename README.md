# test-jsdoc

1. `main.js` - Source code with import of types

  ```js
  /** @type {import("./types").Customer} */
  const theCustomer = {};
  ```

2. `types.d.ts` - Definition of JSDoc

  ```ts
  export interface Customer {
    name: string;
    email: string;
  }
  ```
