---
title: minify-maven-plugin
categories: ['java']
---
## [minify-maven-plugin](https://github.com/samaxes/minify-maven-plugin)

### Combine and minimize JavaScript and CSS files for faster page loading.


Minify Maven Plugin combines and minimizes your CSS and JavaScript files for faster page loading. It produces a merged and a minified version of your CSS and JavaScript resources which can be re-used across your project.

Under the hood, it uses the [YUI Compressor](http://yui.github.com/yuicompressor/) and [Google Closure Compiler](https://developers.google.com/closure/compiler/) but has a layer of abstraction around these tools which allows for other tools to be added in the future.
