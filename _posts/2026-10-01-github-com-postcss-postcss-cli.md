---
title: postcss-cli
categories: ['javascript', 'cli', 'postcss']
---
## [postcss-cli](https://github.com/postcss/postcss-cli)

### CLI for postcss


If you need to pass options to your plugins, or have a long plugin chain, you'll want to use a configuration file.

**postcss.config.js**

```js
module.exports = {
  parser: 'sugarss',
  plugins: [
    require('postcss-import')({ ...options }),
    require('postcss-url')({ url: 'copy', useHash: true }),
  ],
}
```

Note that you **can not** set the `from` or `to` options for postcss in the config file. They are set automatically based on the CLI arguments.
