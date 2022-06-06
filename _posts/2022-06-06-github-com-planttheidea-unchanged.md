---
title: unchanged
categories: ['typescript', 'javascript', 'functional-programming']
---
## [unchanged](https://github.com/planttheidea/unchanged)

### A tiny, fast, unopinionated handler for updating JS objects and arrays immutably


A tiny (~2.1kB minified+gzipped), [fast](https://github.com/planttheidea/unchanged/blob/master/benchmark_results.csv), unopinionated handler for updating JS objects and arrays immutably.

Supports nested key paths via path arrays or [dotty syntax](https://github.com/planttheidea/pathington), and all methods are curriable (with placeholder support) for composability. Can be a drop-in replacement for the `lodash/fp` methods `get`, `set`, `merge`, and `omit` with a 90% smaller footprint.
