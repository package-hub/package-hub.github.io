---
title: crisp-react
categories: ['typescript', 'react', 'express']
---
## [crisp-react](https://github.com/winwiz1/crisp-react)

### React boilerplate written in TypeScript with a variety of Jamstack and full stack deployments. Comes with SSR and without need to learn a framework. Helps to split a monolithic React app into multiple SPAs and avoid vendor lock-in.

Crisp React can optionally split a monolithic React app into multiple Single Page Applications (SPAs) and selectively prerender the landing/index page of any SPA at the build time. This innovative flexibility can offer the best performance for many websites, more about it later. Yet it doesn't come at the price of complicating the solution which remains as simple as a React application could possibly be.

For example, the Router is arguably one of the most important SPA components because it drives the application by controlling its page switching. Crisp React doesn't use a custom Router, in each SPA the routing is managed by a separate instance of [React Router](https://reactrouter.com/) which is the de facto standard for React SPAs.

The value offered by Crisp React is not limited to performance. On the one hand, the value comes from what this solution doesn't bring about. There is no need to learn a framework, depend on it and use non-portable programming constructs in the React components you write, therefore no vendor lock-in. On the other hand, the list of useful features includes: