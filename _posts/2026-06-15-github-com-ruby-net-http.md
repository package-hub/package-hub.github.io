---
title: net-http
categories: ['ruby', 'hacktoberfest']
---
## [net-http](https://github.com/ruby/net-http)

### Net::HTTP provides a rich library which can be used to build HTTP user-agents.


Net::HTTP provides a rich library which can be used to build HTTP
user-agents.  For more details about HTTP see
[RFC9110 HTTP Semantics](https://www.ietf.org/rfc/rfc9110.html) and
[RFC9112 HTTP/1.1](https://www.ietf.org/rfc/rfc9112.html).

Net::HTTP is designed to work closely with URI.  URI::HTTP#host,
URI::HTTP#port and URI::HTTP#request_uri are designed to work with
Net::HTTP.

If you are only performing a few GET requests you should try OpenURI.
