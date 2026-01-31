---
title: slug-generator
categories: ['php', 'library', 'slug']
---
## [slug-generator](https://github.com/ausi/slug-generator)

### Slug Generator Library for PHP, based on Unicode’s CLDR data


The delimiter can be any string, it is used to separate words.
It gets stripped from the beginning and the end of the slug.

```php
$generator->generate('Hello World!');                         // Result: hello-world
$generator->generate('Hello World!', ['delimiter' => '_']);   // Result: hello_world
$generator->generate('Hello World!', ['delimiter' => '%20']); // Result: hello%20world
```
