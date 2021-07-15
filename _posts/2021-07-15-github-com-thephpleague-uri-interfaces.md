---
title: uri-interfaces
categories: ['php', 'uri', 'uri-interfaces']
---
## [uri-interfaces](https://github.com/thephpleague/uri-interfaces)

### League URI Interfaces


The `UriInterface` interface models generic URIs as specified in [RFC 3986](http://tools.ietf.org/html/rfc3986).
The interface provides methods for interacting with the various URI parts, which will obviate the need for repeated parsing of the URI.
It also specifies:
 
 - a `__toString()` method for casting the modeled URI to its string representation.
 - a `jsonSerialize()` method to improve interoperability with [WHATWG URL Living standard](https://url.spec.whatwg.org/)
