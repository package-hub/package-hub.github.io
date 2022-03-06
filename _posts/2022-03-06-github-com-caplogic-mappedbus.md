---
title: Mappedbus
categories: ['java', 'ipc', 'memory-mapped-file']
---
## [Mappedbus](https://github.com/caplogic/Mappedbus)

### Mappedbus is a low latency message bus for Java microservices utilizing shared memory. http://mappedbus.io


Mappedbus was inspired by [Java Chronicle](https://github.com/OpenHFT/Chronicle-Queue) with the main difference that it's designed to efficiently support multiple writers – enabling use cases where the order of messages produced by multiple processes are important.

The throughput (on a laptop, i7-4558U @ 2.8 GHz) between a single producer writing at full speed and a single consumer is around 14 million messages per second (a small message consisting of three integer fields), and the average read/write latency is around 70 ns per message.

Mappedbus does not create any objects after startup and therefore has Zero GC impact.
