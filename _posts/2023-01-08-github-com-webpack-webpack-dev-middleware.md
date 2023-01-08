---
title: webpack-dev-middleware
categories: ['javascript', 'webpack', 'webpack-dev-middleware']
---
## [webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware)

### A development middleware for webpack


An express-style development middleware for use with [webpack](https://webpack.js.org)
bundles and allows for serving of the files emitted from webpack.
This should be used for **development only**.

Some of the benefits of using this middleware include:

- No files are written to disk, rather it handles files in memory
- If files changed in watch mode, the middleware delays requests until compiling
  has completed.
- Supports hot module reload (HMR).
