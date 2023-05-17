---
title: react-stdio
categories: ['javascript']
---
## [react-stdio](https://github.com/ReactTraining/react-stdio)

### Render React.js components on any backend


[build-badge]: https://img.shields.io/travis/ReactTraining/react-stdio/master.svg?style=flat-square
[build]: https://travis-ci.org/ReactTraining/react-stdio
[npm-badge]: https://img.shields.io/npm/v/react-stdio.svg?style=flat-square
[npm]: https://www.npmjs.org/package/react-stdio

[react-stdio](https://npmjs.org/package/react-stdio) lets you render [React](https://reactjs.org/) components on the server, regardless of the backend technology you're using.

As its name suggests, other processes communicate with react-stdio using standard streams. The protocol is JSON, so any environment that can spawn a child process and write JSON to its stdin can use the server. Requests are handled serially, so responses are issued in the same order requests are received.
