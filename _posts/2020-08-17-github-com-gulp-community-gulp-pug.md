---
title: gulp-pug
categories: ['javascript', 'gulp', 'gulp-plugin']
---
## [gulp-pug](https://github.com/gulp-community/gulp-pug)

### Gulp plugin for compiling Pug templates

> Gulp plugin for compiling Pug templates

This Gulp plugin enables you to compile your Pug templates into HTML or JS, with support for template locals, custom Pug filters, AMD wrapping, and others.  Here is a simple example using `gulp-pug`:

```javascript
var pug = require('gulp-pug');

gulp.task('views', function buildHTML() {
  return gulp.src('views/*.pug')
  .pipe(pug({
    // Your options in here.
  }))
});
```
