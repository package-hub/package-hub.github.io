---
title: Cm_Cache_Backend_Redis
categories: ['php']
---
## [Cm_Cache_Backend_Redis](https://github.com/colinmollenhour/Cm_Cache_Backend_Redis)

### A Zend_Cache backend for Redis with full support for tags (works great with Magento)


 - Can take advantage of the [phpredis PECL extension](https://github.com/phpredis/phpredis) for best performance if it is installed.
 - Falls back to standalone PHP if phpredis isn't available using the [Credis](https://github.com/colinmollenhour/credis) library.
 - Tagging is fully supported, implemented using the Redis "set" and "hash" data types for efficient tag management.
 - Key expiration is handled automatically by Redis.
 - Supports unix socket connection for even better performance on a single machine.
 - Supports configurable compression for memory savings. Can choose between gzip, lzf, l4z, snappy and zstd and can change configuration without flushing cache.
 - Uses transactions to prevent race conditions between saves, cleans or removes causing unexpected results.
 - Supports a configurable "auto expiry lifetime" which, if set, will be used as the TTL when the key otherwise wouldn't expire. In combination with "auto expiry refresh on load" offers a more sane cache management strategy for Magento's `Enterprise_PageCache` module.
 - Supports reading from slaves, can be overridden at run time by setting the 'safe_load' directive.
 - Can read connection info from Redis Sentinel for automatic failovers.
 - __Unit tested!__
