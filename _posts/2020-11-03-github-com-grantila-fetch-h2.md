---
title: fetch-h2
categories: ['typescript']
---
## [fetch-h2](https://github.com/grantila/fetch-h2)

### HTTP/1+2 Fetch API client for Node.js


[Fetch API](https://developer.mozilla.org/docs/Web/API/Fetch_API) implementation for Node.js using the built-in `http`, `https` and `http2` packages without any compatibility layer.

`fetch-h2` handles HTTP/1(.1) and HTTP/2 connections transparently since 2.0. By default (although configurable) a url to `http://` uses HTTP/1(.1) and for the very uncommon plain-text HTTP/2 (called _h2c_), `http2://` can be provided. The library supports ALPN negotation, so `https://` will use either HTTP/1(.1) or HTTP/2 depending on what the server supports. By default, HTTP/2 is preferred.

The library handles sessions transparently and re-uses sockets when possible.

`fetch-h2` tries to adhere to the [Fetch API](https://developer.mozilla.org/docs/Web/API/Fetch_API) very closely, but extends it slightly to fit better into Node.js (e.g. using streams).

Regardless of whether you're actually interested in the Fetch API per se or not, as long as you want to handle HTTP/2 client requests in Node.js, this module is a lot easier and more natural to use than the native built-in [`http2`](https://nodejs.org/dist/latest-v10.x/docs/api/http2.html) module which is low-level in comparison.

`fetch-h2` supports cookies (per-context, see below), so when the server sends 'set-cookie' headers, they are saved and automatically re-sent, even after disconnect. They are however only persisted in-memory.

By default, `fetch-h2` will accept `gzip` and `deflate` encodings (and Brolti `br` if running on Node.js 11.7 or later), and decode transparently. If you want to allow Brotli for older versions node Node.js, use the [`fetch-h2-br`](https://www.npmjs.com/package/fetch-h2-br) package.

