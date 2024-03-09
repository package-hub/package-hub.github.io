---
title: babel-plugin-add-module-exports
categories: ['javascript', 'babel-plugin']
---
## [babel-plugin-add-module-exports](https://github.com/59naga/babel-plugin-add-module-exports)

### 【v0.2 no longer maintained】 Fix babel/babel#2212 - Follow the babel@5 behavior for babel@6


**However, the plugin doesn't change the pure-esmodule**.
this plugin makes changes only when exists `exports.default` (in other words, using [commonjs](https://babeljs.io/docs/en/babel-plugin-transform-es2015-modules-commonjs/)).

```json
{
  "presets": [["@babel/env", { "modules": false }]],
  "plugins": ["add-module-exports"]
}
```

into

```js
export default 'foo'
```

`1.0.0` Currently support is `commonjs` and `umd`.
Doesn't support `amd`, `systemjs` modules(don't use. there are no plans to support at the moment).
