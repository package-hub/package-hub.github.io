---
title: worker-plugin
categories: ['javascript', 'webpack', 'workers']
---
## [worker-plugin](https://github.com/GoogleChromeLabs/worker-plugin)

### 👩‍🏭 Adds native Web Worker bundling support to Webpack.


Automatically compiles modules loaded in Web Workers:

```js
const worker = new Worker('./foo.js', { type: 'module' });
                          ^^^^^^^^^^
                          gets bundled using webpack
```

The best part? That worker constructor works just fine without bundling turned on, but when bundled the result is **supported in all browsers** that support Web Workers - all the way back to IE 10!

Workers with fully dynamic URLs, Blob URLs, data URLs or with no `{ type:'module' }` option are left unchanged.
