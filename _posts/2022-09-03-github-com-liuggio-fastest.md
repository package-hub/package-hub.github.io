---
title: fastest
categories: ['php', 'hacktoberfest', 'hacktoberfest2020']
---
## [fastest](https://github.com/liuggio/fastest)

### Simple parallel testing execution... with some goodies for functional tests.


**Execute parallel commands, creating a Process for each Processor (with some goodies for functional tests).**

``` bash
find tests/ -name "*Test.php" | ./vendor/liuggio/fastest/fastest "vendor/phpunit/phpunit/phpunit -c app {};"
```

Fastest works with **any available testing tool**! It just executes it in parallel.

It is optimized for functional tests, giving an easy way to work with N databases in parallel.
