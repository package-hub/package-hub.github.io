---
title: manticoresearch-php
categories: ['php', 'search']
---
## [manticoresearch-php](https://github.com/manticoresoftware/manticoresearch-php)

### Official PHP client for Manticore Search


```php
require_once __DIR__ . '/vendor/autoload.php';

$config = ['host'=>'127.0.0.1','port'=>9308];
$client = new \Manticoresearch\Client($config);
$index = $client->index('movies');
```
