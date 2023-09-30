---
title: redis-py-cluster
categories: ['python', 'redis', 'redis-cluster']
---
## [redis-py-cluster](https://github.com/Grokzen/redis-py-cluster)

### Python cluster client for the official redis cluster. Redis 3.0+. 


In the upstream package *redis-py* that this librar extends, they have since version `* 4.1.0 (Dec 26, 2021)` ported in this code base into the main branch. That basically ends the need for this package if you are using any version after that release as it is natively supported there. If you are upgrading your redis-py version you should plan in time to migrate out from this package into their package. The move into the first released version should be seamless with very few and small changes required. This means that the release `2.1.x` is the very last major release of this package. This do not mean that there might be some small support version if that is needed to sort out some critical issue here. This is not expected as the development time spent on this package in the last few years have been very low. This repo will not be put into a real github Archive mode but this repo should be considered in archive state.

I want to give a few big thanks to some of the people that has provided many contributions, work, time and effort into making this project into what it is today. First is one of the main contributors 72Squared and his team who helped to build many of the core features and trying out new and untested code and provided many optimizations. The team over at AWS for putting in the time and effort and skill into porting over this to `redis-py`. The team at RedisLabs for all of their support and time in creating a fantastic redis community the last few years. Antirez for making the reference client which this repo was written and based on and for making one of my favorite databases in the ecosystem. And last all the contributions and use of this repo by the entire community.

