---
title: redlock-rb
categories: ['ruby', 'redis', 'lock']
---
## [redlock-rb](https://github.com/leandromoreira/redlock-rb)

### Redlock is a redis-based distributed lock implementation in Ruby. More than 15M downloads.


> Distributed locks are a very useful primitive in many environments where different processes require to operate  with shared resources in a mutually exclusive way.
>
> There are a number of libraries and blog posts describing how to implement a DLM (Distributed Lock Manager) with Redis, but every library uses a different approach, and many use a simple approach with lower guarantees compared to what can be achieved with slightly more complex designs.

This is an implementation of a proposed [distributed lock algorithm with Redis](http://redis.io/topics/distlock). It started as a fork from [antirez implementation.](https://github.com/antirez/redlock-rb)
