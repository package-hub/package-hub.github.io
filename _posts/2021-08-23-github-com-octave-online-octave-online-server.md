---
title: octave-online-server
categories: ['javascript']
---
## [octave-online-server](https://github.com/octave-online/octave-online-server)

### The infrastructure that powers Octave Online, octave-online.net


There are three separate components of Octave Online Server:

1. **Client**: Code that runs in the browser.
2. **Front Server**: Authentication, client session handling.
3. **Back Server**: File I/O, Octave process handling.

*Communication:* The Client and Front Server communicate primarily with WebSockets via [socket.io](https://socket.io); the Front Server and Back Server communicate primarily with [Redis PubSub](https://redis.io/topics/pubsub).  User account information is stored in [MongoDB](https://www.mongodb.com) and is accessed primarily from the Front Server.  User files are stored in [Git on the Server](https://git-scm.com/book/en/v1/Git-on-the-Server) and are accessed primarily from the Back Server.

*Scaling:* Front Servers and Back Servers can be scaled independently (in general, you need more Back Servers than Front Servers).  It is also possible to run both the Front Server and the Back Server on the same computer.

*Languages:* All code is written with JavaScript technologies, although for historical reasons, the three components use different flavors of JavaScript.  The Client uses ES5; the Front Server uses TypeScript; and the Back Server uses ES6.
