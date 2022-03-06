---
title: BigInteger.js
categories: ['javascript']
---
## [BigInteger.js](https://github.com/peterolson/BigInteger.js)

### An arbitrary length integer library for Javascript


[travis-url]: https://travis-ci.org/peterolson/BigInteger.js
[travis-img]: https://travis-ci.org/peterolson/BigInteger.js.svg?branch=master
[coveralls-url]: https://coveralls.io/github/peterolson/BigInteger.js?branch=master
[coveralls-img]: https://coveralls.io/repos/peterolson/BigInteger.js/badge.svg?branch=master&service=github
[downloads-url]: https://www.npmjs.com/package/big-integer
[downloads-img]: https://img.shields.io/npm/dm/big-integer.svg

**BigInteger.js** is an arbitrary-length integer library for Javascript, allowing arithmetic operations on integers of unlimited size, notwithstanding memory and time limitations.

**Update (December 2, 2018):** [`BigInt` is being added as a native feature of JavaScript](https://tc39.github.io/proposal-bigint/). This library now works as a polyfill: if the environment supports the native `BigInt`, this library acts as a thin wrapper over the native implementation.
