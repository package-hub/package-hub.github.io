---
title: main-bower-files
categories: ['javascript']
---
## [main-bower-files](https://github.com/ck86/main-bower-files)

### Getting all main bower files


```javascript
var mainBowerFiles = require('main-bower-files');
var files = mainBowerFiles([[filter, ]options][, callback]);
```

If first argument is type of `String`, `Array` or `RegExp` it will be used as a filter, otherwise it will be used as options.

This will read your `bower.json`, iterate through your dependencies and returns an array of files defined in the main property of the packages `bower.json`.

You can override the behavior if you add an `overrides` property to your own `bower.json`.
