---
title: node-mocks-http
categories: ['javascript']
---
## [node-mocks-http](https://github.com/howardabrams/node-mocks-http)

### Mock 'http' objects for testing Express routing functions


This project is available as a
[NPM package][npm-url].

```bash
$ npm install --save-dev node-mocks-http
```

> Our example includes `--save-dev` based on the assumption that **node-mocks-http** will be used as a development dependency..

After installing the package include the following in your test files:

```js
var httpMocks = require('node-mocks-http');
```
