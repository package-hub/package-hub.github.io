---
title: php-mock
categories: ['php', 'mock', 'builtin-functions']
---
## [php-mock](https://github.com/php-mock/php-mock)

### Mock built-in PHP functions (e.g. time(), exec() or rand())


PHP-Mock is a testing library which mocks non deterministic built-in PHP functions like
`time()` or `rand()`. This is achieved by [PHP's namespace fallback policy](http://php.net/manual/en/language.namespaces.fallback.php):

> PHP will fall back to global functions […]
> if a namespaced function […] does not exist.

PHP-Mock uses that feature by providing the namespaced function. I.e. you have
to be in a **non global namespace** context and call the function
**unqualified**:

```php
namespace foo;

$time = time(); // This call can be mocked, a call to \time() can't.
```
