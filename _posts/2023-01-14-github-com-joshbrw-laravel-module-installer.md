---
title: laravel-module-installer
categories: ['php']
---
## [laravel-module-installer](https://github.com/joshbrw/laravel-module-installer)

### Installs Laravel modules created for nwidart/laravel-modules into the Modules/ directory.


The purpose of this package is to allow for easy installation of standalone Modules into the [Laravel Modules](https://github.com/nWidart/laravel-modules) package. This package will ensure that your module is installed into the `Modules/` directory instead of `vendor/`.

You can specify an alternate directory by including a `module-dir` in the extra data in your composer.json file:

    "extra": {
        "module-dir": "Custom"
    }

