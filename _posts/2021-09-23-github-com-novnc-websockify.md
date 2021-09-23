---
title: websockify
categories: ['python', 'websockify', 'websockets']
---
## [websockify](https://github.com/novnc/websockify)

### Websockify is a WebSocket to TCP proxy/bridge. This allows a browser to connect  to any application/server/service.


websockify was formerly named wsproxy and was part of the
[noVNC](https://github.com/novnc/noVNC) project.

At the most basic level, websockify just translates WebSockets traffic
to normal socket traffic. Websockify accepts the WebSockets handshake,
parses it, and then begins forwarding traffic between the client and
the target in both directions.
