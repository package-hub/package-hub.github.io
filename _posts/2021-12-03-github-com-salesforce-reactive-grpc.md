---
title: reactive-grpc
categories: ['java', 'grpc-java', 'rxjava2']
---
## [reactive-grpc](https://github.com/salesforce/reactive-grpc)

### Reactive stubs for gRPC

Reactive gRPC is a suite of libraries for using gRPC with [Reactive Streams](http://www.reactive-streams.org/) programming libraries. Using a protocol buffers
compiler plugin, Reactive gRPC generates alternative gRPC bindings for each reactive technology.
The reactive bindings support unary and streaming operations in both directions. Reactive gRPC also builds on top of gRPC's
back-pressure support, to deliver end-to-end back-pressure-based flow control in line with Reactive Streams
back-pressure model.

Reactive gRPC supports the following reactive programming models:

* [RxJava 2](https://github.com/salesforce/reactive-grpc/tree/master/rx-java)
* [Spring Reactor](https://github.com/salesforce/reactive-grpc/tree/master/reactor)

[Akka gRPC](https://github.com/akka/akka-grpc) is now mature and production ready. Use that for Akka-based services.
