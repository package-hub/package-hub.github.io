---
title: copy-to-clipboard
categories: ['javascript']
---
## [copy-to-clipboard](https://github.com/sudodoki/copy-to-clipboard)

### Copy stuff into clipboard from your browser using JS


Simple module exposing `copy` function that will try to use [execCommand](https://developer.mozilla.org/en-US/docs/Web/API/Document/execCommand#) with fallback to IE-specific `clipboardData` interface and finally, resort to usual `prompt` with proper text content and message.
