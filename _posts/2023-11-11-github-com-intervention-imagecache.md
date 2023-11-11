---
title: imagecache
categories: ['php']
---
## [imagecache](https://github.com/Intervention/imagecache)

### Caching extension for the Intervention Image Class


Intervention Image Cache extends the [Intervention Image Class](https://github.com/Intervention/image/) package to be capable of image caching functionality.

The library uses the [Illuminate/Cache](https://github.com/illuminate/cache/) package and can be easily integrated into the [Laravel Framework](https://laravel.com/). Based on your Laravel cache configuration you are able to choose between Filesystem, Database, Memcached or Redis for the temporary buffer store.

The principle is simple. Every method call to the Intervention Image class is captured and checked by the caching interface. If this particular sequence of operations already have taken place, the data will be loaded directly from the cache instead of a resource-intensive image operation.
