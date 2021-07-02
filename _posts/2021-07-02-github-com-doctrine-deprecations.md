---
title: deprecations
categories: ['php']
---
## [deprecations](https://github.com/doctrine/deprecations)

### Thin library around different deprecation strategies


A small (side-effect free by default) layer on top of
`trigger_error(E_USER_DEPRECATED)` or PSR-3 logging.

- no side-effects by default, making it a perfect fit for libraries that don't know how the error handler works they operate under
- options to avoid having to rely on error handlers global state by using PSR-3 logging
- deduplicate deprecation messages to avoid excessive triggering and reduce overhead

We recommend to collect Deprecations using a PSR logger instead of relying on
the global error handler.
