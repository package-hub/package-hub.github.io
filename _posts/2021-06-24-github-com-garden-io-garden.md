---
title: garden
categories: ['typescript', 'kubernetes', 'developer-tools']
---
## [garden](https://github.com/garden-io/garden)

### Automation for Kubernetes development and testing. Spin up production-like environments for development, testing, and CI on demand. Use the same configuration and workflows at every step of the process. Speed up your builds and test runs via shared result caching.


Users typically implement Garden for one or more of the following:

- **In-cluster Development:** With Garden, developers working on Kubernetes applications can spin up a production-like, namespaced environment in a cluster, on demand. With in-cluster environments, devs don't need to run Docker, Kubernetes, or a complex distributed application on their laptops. 
- **Fast & Consistent CI Pipelines:** Garden makes it possible to use the same configuration for development, testing, and CI, which ensures consistency across different environments. You can run the exact same tests from a production-like development environment that will later be run in CI, meaning a much more predictable pipeline. In addition, Garden's shared cached results for image builds and tests means that your CI pipeline will run much faster, reducing cycle time and getting new features merged more quickly.
- **Integration Testing:** Because Garden environments capture the full configuration of an application, it’s possible to run proper integration tests with runtime dependencies–no mocking or stubbing required. A developer can run integration tests with a single command before creating a PR to get fast feedback and iterate more quickly, or integration tests can be run against a feature branch every time a PR is created.
- **Manual QA & Code Review:** Garden enables developers, QA engineers, and product managers to spin up production-like preview environments on demand. These preview environments can be used, for example, to QA any part of an application that can’t be covered by automated testing (e.g. complex frontend functionality) or in cases when client developers need a fully-functioning backend to validate new features. Product managers can use Garden preview environments to review a working version of an application for pre-release acceptance testing. 
