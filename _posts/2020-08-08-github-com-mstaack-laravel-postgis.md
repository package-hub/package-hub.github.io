---
title: laravel-postgis
categories: ['php']
---
## [laravel-postgis](https://github.com/mstaack/laravel-postgis)

### Postgis extensions for laravel. Aims to make it easy to work with geometries from laravel models.


 * Work with geometry classes instead of arrays.
```php
$model->myPoint = new Point(1,2);  //lat, long
```

* Adds helpers in migrations.
```php
$table->polygon('myColumn');
```
