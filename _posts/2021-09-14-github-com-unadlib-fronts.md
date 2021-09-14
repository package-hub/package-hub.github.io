---
title: fronts
categories: ['typescript', 'mircofrontend', 'react']
---
## [fronts](https://github.com/unadlib/fronts)

### A progressive  micro frontends framework for building Web applications


Among the many micro frontends solutions, [single-spa](https://github.com/single-spa/single-spa) and [Module Federation](https://webpack.js.org/concepts/module-federation/) are the best of them.

[single-spa](https://github.com/single-spa/single-spa) is a micro frontends framework based on router configuration. The centralization of configuration brings some limitations, such as it is difficult to granulate nestable micro frontends, module granularity control, module sharing, and so on.

In 2019, Zack Jackson proposed and implemented Module Federation. Module Federation is a completely different concept from single-spa, and allows a JavaScript application to dynamically load code from another application. It completely solves the problem of code dependency sharing and runtime modularity. The idea is true - [A game-changer in JavaScript architecture](https://medium.com/swlh/webpack-5-module-federation-a-game-changer-to-javascript-architecture-bcdd30e02669) as mentioned in Zack Jackson's article. And it's currently supported by Webpack, Next.js, and Rollup.

Although the Module Federation concept is so amazing, it has not yet gone further to provide a more complete and fully targeted micro frontends framework implementation, and this is what Fronts is trying to do.
