---
title: mockttp
categories: ['typescript', 'mock-server', 'fake-server']
---
## [mockttp](https://github.com/httptoolkit/mockttp)

### Powerful friendly HTTP mock server & proxy library


> _Part of [HTTP Toolkit](https://httptoolkit.tech): powerful tools for building, testing & debugging HTTP(S)_

**Mockttp lets you intercept, transform or test HTTP requests & responses in JavaScript - quickly, reliably & anywhere.**

You can use Mockttp for integration testing, by intercepting real requests as part of your test suite, or you can use Mockttp to build custom HTTP proxies that capture, inspect and/or rewrite HTTP in any other kind of way you like.

HTTP testing is the most common and well supported use case. There's a lot of tools to test HTTP, but typically by stubbing the HTTP functions in-process at the JS level. That ties you to a specific environment, doesn't truly test the real requests that you code would send, and only works for requests made in the same JS process. It's inflexible, limiting and inaccurate, and often unreliable & tricky to debug too.

Mockttp meanwhile allows you to do accurate true integration testing, writing one set of tests that works out of the box in node or browsers, with support for transparent proxying & HTTPS, strong typing & promises throughout, fast & safe parallel testing, and with debuggability built-in at every stage.

Mockttp is also battle-tested as a scriptable rewriting proxy, powering all the HTTP internals of [HTTP Toolkit](https://httptoolkit.tech). Anything you can do with HTTP Toolkit, you can automate with Mockttp as a headless script.
