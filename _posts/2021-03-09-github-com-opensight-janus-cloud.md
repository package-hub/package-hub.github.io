---
title: janus-cloud
categories: ['python', 'webrtc', 'janus']
---
## [janus-cloud](https://github.com/OpenSight/janus-cloud)

### a cluster solution for Janus WebRTC server, by API proxy approach


Janus-proxy is responsible for signal handling, which communicates with the WebRTC client and relay the signal from client to the backend Janus servers. It conceals the detail of the backend Janus server cluster and output the same interface with the original Janus server. Janus-proxy is usually running on a standalone machine which is between the WebRTC client and the backend Janus servers. The WebRTC client interact with Janus-proxy for signal, but transfer to/from the real Janus Server for media. Janus-proxy has the following features/limitation:

- Only provide the WebSocket(s) API, not provide RESTful, RabbitMQ, MQTT, Nanomsg and UnixSockets like Janus
- Communicate with the backend Janus server by WebSocket
- Pluggable. Its business functionality is implemented by the various plugins
- Support RESTful admin interface
- Scalable. The backend Janus server can be added/removed to/from Janus-proxy dynamically
- Support multi algorithm to choose which backend server to relay signal
