---
title: meekrodb
categories: ['php']
---
## [meekrodb](https://github.com/SergeyTsalkov/meekrodb)

### MeekroDB -- The Simple PHP MySQL Library

Include the `db.class.php` file into your project and set it up like this:

```php
require_once 'db.class.php';
DB::$dsn = 'mysql:host=localhost;dbname=meekrodb';
DB::$user = 'my_database_user';
DB::$password = 'my_database_password';
```
