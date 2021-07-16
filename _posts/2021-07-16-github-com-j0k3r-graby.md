---
title: graby
categories: ['php', 'text-rss', 'extract-website']
---
## [graby](https://github.com/j0k3r/graby)

### Graby helps you extract article content from web pages


Full-Text RSS works great as a standalone application. But when you need to encapsulate it in your own library it's a mess. You need this kind of ugly thing:

```php
$article = 'http://www.bbc.com/news/entertainment-arts-32547474';
$request = 'http://example.org/full-text-rss/makefulltextfeed.php?format=json&url='.urlencode($article);
$result  = @file_get_contents($request);
```

Also, if you want to understand how things work internally, it's really hard to read and understand. And finally, there are **no tests** at all.

That's why I made this fork:

1. Easiest way to integrate it (using composer)
2. Fully tested
3. (hopefully) better to understand
4. A bit more decoupled
