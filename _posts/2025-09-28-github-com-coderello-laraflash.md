---
title: laraflash
categories: ['php', 'laraflash', 'laravel']
---
## [laraflash](https://github.com/coderello/laraflash)

### ⚡ Flash messages on steroids.


You can install this package via composer using this command:

```bash
composer require coderello/laraflash 
```

After that you need to register the `\Coderello\Laraflash\Middleware\HandleLaraflash::class` middleware after the `\Illuminate\Session\Middleware\StartSession::class` one in the `app\Http\Kernel.php`

You can publish the config file with:

```bash
php artisan vendor:publish --tag="laraflash-config"
```
