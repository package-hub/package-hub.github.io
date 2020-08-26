---
title: webpack-node-externals
categories: ['javascript', 'webpack', 'node']
---
## [webpack-node-externals](https://github.com/liady/webpack-node-externals)

### Easily exclude node modules in Webpack

```sh
npm install webpack-node-externals --save-dev
```

In your `webpack.config.js`:
```js
var nodeExternals = require('webpack-node-externals');
...
module.exports = {
    ...
    target: 'node', // in order to ignore built-in modules like path, fs, etc.
    externals: [nodeExternals()], // in order to ignore all modules in node_modules folder
    ...
};
```
And that's it. All node modules will no longer be bundled but will be left as `require('module')`.
