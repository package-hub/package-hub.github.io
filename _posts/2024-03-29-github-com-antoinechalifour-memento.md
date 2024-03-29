---
title: memento
categories: ['typescript', 'memento', 'node']
---
## [memento](https://github.com/antoinechalifour/memento)

### Memento is a development-only tool that caches HTTP calls once they have been executed.


When building a UI or working on any project that rely on external services, some things can slow us down:

- the API **may not be stable** at the moment
- the API **may apply harsh rate-limiting** (and that's terrible if you forget the dependency array in your `React.useEffect` 😉)
- ...or you may be working on a train or plane where **the network is not reliable**.

**Memento has been built to solve these problems.**

Memento acts as a development buddy that remembers the requests that your application is sending, the server response, and will respond to your app without the need for requests to go over the internet.

_Pro-tip: Memento may also be used for [stubbing external services for integration or end-to-end testing](./examples/stub-external-services) 🎉_
