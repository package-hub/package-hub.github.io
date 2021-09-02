---
title: browserless
categories: ['javascript', 'puppeteer', 'puppeteer-core']
---
## [browserless](https://github.com/microlinkhq/browserless)

### A browser driver on top of puppeteer, ready for production scenarios.


- Puppeteer-like API for common tasks ([text](texturl-options), [screenshot](#screenshoturl-options), [html](#htmlurl-options), [pdf](#pdfurl-options)).
- Built-in [evasion](#evasions) techniques to prevent being blocked.
- Built-in [adblocker](#adblock) for canceling unnecessary requests.
- Support for proxy (HTTP/HTTPS/SOCKs) per page.
- Shell interaction via [Browserless CLI](command-line-interface).
- Easy [Google Lighthouse](#lighthouse) integration.
- Automatic retry & error handling.
- Configurable [pooling](#pool-of-instances) support.
- Sensible good defaults.
