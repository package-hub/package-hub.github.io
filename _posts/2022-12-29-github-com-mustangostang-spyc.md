---
title: spyc
categories: ['php']
---
## [spyc](https://github.com/mustangostang/spyc)

### A simple YAML loader/dumper class for PHP


Using Spyc is trivial:

```php
<?php
require_once "spyc.php";
$Data = Spyc::YAMLLoad('spyc.yaml');
```

or (if you prefer functional syntax)

```php
<?php
require_once "spyc.php";
$Data = spyc_load_file('spyc.yaml');
```
