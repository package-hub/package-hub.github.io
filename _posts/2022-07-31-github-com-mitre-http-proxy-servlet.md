---
title: HTTP-Proxy-Servlet
categories: ['java']
---
## [HTTP-Proxy-Servlet](https://github.com/mitre/HTTP-Proxy-Servlet)

### Smiley's HTTP Proxy implemented as a Java servlet


The following is a list of parameters that can be configured

+ log: A boolean parameter name to enable logging of input and target URLs to the servlet log.
+ forwardip: A boolean parameter name to enable forwarding of the client IP
+ preserveHost: A boolean parameter name to keep HOST parameter as-is  
+ preserveCookies: A boolean parameter name to keep COOKIES as-is
+ http.protocol.handle-redirects: A boolean parameter name to have auto-handle redirects
+ http.socket.timeout: A integer parameter name to set the socket connection timeout (millis)
+ http.read.timeout: A integer parameter name to set the socket read timeout (millis)
+ http.connectionrequest.timeout: A integer parameter name to set the connection request timeout (millis)
+ http.maxConnections: A integer parameter name to set max connection number
+ useSystemProperties: A boolean parameter whether to use JVM-defined system properties to configure various networking aspects.
+ targetUri: The parameter name for the target (destination) URI to proxy to.

