---
title: dpdm
categories: ['typescript', 'circular', 'visualization']
---
## [dpdm](https://github.com/acrazing/dpdm)

### Detect circular dependencies in your TypeScript projects.


- Supports `CommonJS`, `ESM`.
- Supports `JavaScript` and `TypeScript` completely.
  - Supports TypeScript [path mapping](https://www.typescriptlang.org/docs/handbook/module-resolution.html#path-mapping).
  - Supports ignore TypeScript type dependencies.
- Light weight: use [TypeScript](https://npmjs.com/package/typescript) to parse all modules.
- Fast: use asynchronous API to load modules.
- Stable output: This is compared to `madge`, whose results are completely inconclusive when analyze `TypeScript`.
