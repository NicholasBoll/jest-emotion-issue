To reproduce issue:

```
yarn install
yarn tsc index.ts
```

You'll get the following error:

```
node_modules/@types/jest/index.d.ts:729:15 - error TS2428: All declarations of 'Matchers' must have identical type parameters.

729     interface Matchers<R, T> {
                  ~~~~~~~~

node_modules/jest-emotion/types/index.d.ts:33:15 - error TS2428: All declarations of 'Matchers' must have identical type parameters.

33     interface Matchers<R> {
                 ~~~~~~~~


Found 2 errors.

error Command failed with exit code 2.
```
