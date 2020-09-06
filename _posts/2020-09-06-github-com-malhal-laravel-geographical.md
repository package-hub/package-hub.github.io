---
title: Laravel-Geographical
categories: ['php']
---
## [Laravel-Geographical](https://github.com/malhal/Laravel-Geographical)

### Easily add longitude and latitude columns to your records and use inherited functionality for calculating distances

Easily add longitude and latitude columns to your records and use inherited functionality for calculating distances.

First either update your database or add this to a migration for each model:

```php
$table->double('longitude');
$table->double('latitude');
```

Finally in your model use:
```php
use Geographical;
```
