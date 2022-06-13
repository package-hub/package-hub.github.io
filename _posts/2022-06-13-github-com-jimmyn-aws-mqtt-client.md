---
title: aws-mqtt-client
categories: ['javascript', 'aws-iot', 'aws-mqtt']
---
## [aws-mqtt-client](https://github.com/jimmyn/aws-mqtt-client)

### AWS Websocket Pub/Sub client


[AWS MQTT](http://docs.aws.amazon.com/iot/latest/developerguide/protocols.html) Websocket Pub/Sub with AWS IoT based on [MQTT.js](https://github.com/mqttjs/MQTT.js).
Recently [AWS released support of WebSockets for IoT](https://aws.amazon.com/about-aws/whats-new/2016/01/aws-iot-now-supports-websockets-custom-keepalive-intervals-and-enhanced-console/) service. It is very easy to use as Pub/Sub message system for serverless web applications. You can post new messages from `AWS lambda function` via `http post request` and receive them as websocket messages on client.
