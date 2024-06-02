---
title: sass.js
categories: ['javascript', 'sass', 'libsass']
---
## [sass.js](https://github.com/medialize/sass.js)

### Sass.js - API for emscripted libsass to run in the browser


Sass parser in JavaScript. Have a look at the [Interactive Playground](http://sass.js.org/) to play around with compiling SCSS to CSS in your browser.

This is a convenience API for [emscripted](https://github.com/kripken/emscripten) [libsass](https://github.com/sass/libsass) (at [v3.6.2](https://github.com/sass/libsass/releases/tag/3.6.2)). If you're looking to run Sass in node, you're probably looking for [node-sass](https://github.com/sass/node-sass). Sass.js and node-sass should generate the same results.

A fair warning: minified the worker weighs 4.5MB, gzipped it's still 827KB. If you're on NodeJS, please use the (considerably faster) [node-sass](https://github.com/andrew/node-sass) instead.

You may also be interested in giving [Dart Sass](https://github.com/sass/dart-sass) a shot.

