---
title: asyncawait
categories: ['typescript']
---
## [asyncawait](https://github.com/yortus/asyncawait)

### Callback heaven for Node.js with async/await


Do you need this library?

This library has enabled async/await coding style in Node.js since 2014. But JavaScript now has native async/await.
JS async/await was standardized as part of ES2017, and has been enabled by default in Node.js since v7.6.

So, do you still need this library? If you are just starting to use async/await, the answer is probably no. Use native
async/await. If you're maintaining a codebase that uses this library, or that needs to run on a old version of Node.js,
then you may want to keep using it, but consider migrating to native async/await eventually. If you need deep coroutines
for an advanced scenario, there may still be a case for using this library, since native async/await only supports
shallow coroutine semantics.
