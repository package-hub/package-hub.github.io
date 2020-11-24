---
title: notadd
categories: ['typescript', 'notadd', 'cms']
---
## [notadd](https://github.com/notadd/notadd)

### A microservice development architecture based on nest.js. —— 基于 Nest.js 的微服务开发架构。


[中文文档](./README_zh.md)

Notadd is an open source, Nest.js framework-based microservice development architecture that allows you to build a microservices system using the right modules and addons for different business needs. Notadd officially provides an abstract public service layer. Within the service layer, each module provides the Grpc interface for the Notadd main program to call. For example, a CMS system, you can use the officially provided `nt-module-cms` and `nt-module-user` modules as the underlying service layer. Then use the Notadd main program to write your API layer code according to the `protobuf` message protocol defined by the service layer.
