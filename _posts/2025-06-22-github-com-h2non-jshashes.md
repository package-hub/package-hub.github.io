---
title: jshashes
categories: ['javascript', 'hashing-algorithm', 'hmac']
---
## [jshashes](https://github.com/h2non/jshashes)

### Fast and dependency-free cryptographic hashing library for node.js and browsers (supports MD5, SHA1, SHA256, SHA512, RIPEMD, HMAC)


`jshashes` is lightweight library implementing the most extended [cryptographic hash function](http://en.wikipedia.org/wiki/Cryptographic_hash_function) algorithms in pure JavaScript (ES5 compliant).

The goal is to provide an dependency-free, fast and reliable solution for hash algorithms for both client-side and server-side JavaScript environments. 
The code is fully compatible with the ECMAScript 5 specification and is used in production in browsers and [node.js](http://nodejs.org)/[io.js](http://iojs.org)

If you are looking for a low-level performance library for the server-side, note that node.js/io.js provides its own native module: [`crypto`](http://nodejs.org/api/crypto.html)
