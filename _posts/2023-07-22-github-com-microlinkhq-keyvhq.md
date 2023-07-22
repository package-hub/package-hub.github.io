---
title: keyvhq
categories: ['javascript', 'key-value', 'storage']
---
## [keyvhq](https://github.com/microlinkhq/keyvhq)

### Simple key-value storage with support for multiple backends.


Forked from [keyv](https://github.com/lukechilds/keyv), plus:

- It isn't bloated.
- It supports namespaces.
- It supports TTL based expiry.
- It has a simple Promise based API.
- It handles all JSON types plus `Buffer`.
- It's support a [vary of storages](#official-storage-adapters) adapters.
- It can be [easily embed](#add-cache-support-to-your-module) inside another module.
- It works with any storage that implements the [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map) API.
- it handles database errors (db failures won't kill your app).
- It supports the current active LTS version of Node.js or higher.
- It's suitable as a TTL based cache or persistent key-value store.
