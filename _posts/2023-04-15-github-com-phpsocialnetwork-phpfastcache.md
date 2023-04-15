---
title: phpfastcache
categories: ['php', 'cache', 'redis']
---
## [phpfastcache](https://github.com/PHPSocialNetwork/phpfastcache)

### A high-performance backend cache system.  It is intended for use in speeding up dynamic web applications by alleviating database load.  Well implemented, it can drops the database load to almost nothing, yielding faster page load times for users, better resource utilization.  It is simple yet powerful. 

> As the V9 is **relatively** not compatible with previous versions, please read carefully the [migration guide](./docs/migration/MigratingFromV8ToV9.md) to ensure you the smoothest migration possible.
One of the biggest change is the configuration system which is now an object that replace the primitive array that we used to implement back then. 
Also, please note that the V9 requires at least PHP 8 or higher to works properly.

---------------------------
Simple Yet Powerful PHP Caching Class
---------------------------
More information in [Wiki](https://github.com/PHPSocialNetwork/phpfastcache/wiki)
The simplicity of abstraction: One class for many backend cache. You don't need to rewrite your code many times again.
