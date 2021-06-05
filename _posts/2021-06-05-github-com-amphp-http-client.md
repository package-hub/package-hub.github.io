---
title: http-client
categories: ['php', 'artax', 'amphp']
---
## [http-client](https://github.com/amphp/http-client)

### Async HTTP/1.1+2 client for PHP based on Amp.


 - Supports HTTP/1 and HTTP/2
 - [Requests concurrently by default](examples/concurrency/1-concurrent-fetch.php)
 - [Pools persistent connections (keep-alive @ HTTP/1.1, multiplexing @ HTTP/2)](examples/pooling/1-connection-count.php)
 - [Transparently follows redirects](https://amphp.org/http-client/follow-redirects)
 - [Decodes compressed entity bodies (gzip, deflate)](examples/basic/7-gzip.php)
 - [Exposes headers and message data](examples/basic/1-get-request.php)
 - [Streams entity bodies for memory management with large transfers](examples/streaming/1-large-response.php)
 - [Supports all standard and custom HTTP method verbs](https://amphp.org/http-client/requests#request-method)
 - [Simplifies HTTP form submissions](examples/basic/4-forms.php)
 - [Implements secure-by-default TLS (`https://`)](examples/basic/1-get-request.php)
 - [Supports cookies and sessions](https://github.com/amphp/http-client-cookies)
 - [Functions seamlessly behind HTTP proxies](https://github.com/amphp/http-tunnel)
