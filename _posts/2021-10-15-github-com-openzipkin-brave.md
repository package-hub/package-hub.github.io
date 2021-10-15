---
title: brave
categories: ['java', 'zipkin', 'distributed-tracing']
---
## [brave](https://github.com/openzipkin/brave)

### Java distributed tracing implementation compatible with Zipkin backend services.


Brave is a distributed tracing instrumentation library. Brave typically intercepts production requests to gather timing data,
correlate and propagate trace contexts. While typically trace data is sent to [Zipkin server](https://github.com/openzipkin/zipkin/tree/master/zipkin-server), third-party plugins are available to send to alternate services such as [Amazon X-Ray](https://github.com/openzipkin/zipkin-aws/tree/master/storage/xray-udp).

This repository includes dependency-free Java libraries and instrumentation for common components used in production services. For example, this includes trace filters for Servlet and log correlation for Apache Log4J.

You can look at our [example project](https://github.com/openzipkin/brave-webmvc-example) for how to trace a simple web application.
