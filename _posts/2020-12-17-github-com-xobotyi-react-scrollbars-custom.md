---
title: react-scrollbars-custom
categories: ['typescript', 'customizable', 'scrollbars']
---
## [react-scrollbars-custom](https://github.com/xobotyi/react-scrollbars-custom)

### The best React custom scrollbars component


```bash
npm install react-scrollbars-custom
# or via yarn
yarn add react-scrollbars-custom
```

**INSTALLATION NOTE:**  
This lib is written in ES6+ and delivering with both, transpiled and untranspiled versions:

- `main` field of `package.json` is pointing to transpiled ES3-compatible version with CJS modules resolution;
- `module` field is pointing to transpiled ES3-compatible version with ES modules resolution;
- `esnext` field is pointing to the ES6+ version with ES modules resolution;

Depending on your targets you may have to use [Webpack](https://webpack.js.org/) and/or
[Babel](http://babeljs.io/) to pull untranspiled version of package.  
See some tips on wiring thing up: [https://2ality.com/2017/06/pkg-esnext.html](https://2ality.com/2017/06/pkg-esnext.html)
