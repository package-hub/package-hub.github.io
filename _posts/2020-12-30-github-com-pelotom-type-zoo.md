---
title: type-zoo
categories: ['typescript']
---
## [type-zoo](https://github.com/pelotom/type-zoo)

### A menagerie of useful type operators for TypeScript


TypeScript ships with some handy user-definable type operators: `Partial`, `Readonly`, `Pick` and `Record`. However many other useful operators have been demonstrated in GitHub issue comments and elsewhere. This repository is intended to collect all this folklore in one place, so you can stop copying and pasting these solutions into project after project.

PRs more than welcome! Please note that this library is intended to be fully static, i.e. it has no runtime component, only a type definition file. The idea is that these could all potentially make their way into `lib.d.ts` at some point.
