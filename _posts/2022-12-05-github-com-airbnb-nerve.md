---
title: nerve
categories: ['ruby']
---
## [nerve](https://github.com/airbnb/nerve)

### A service registration daemon that performs health checks; companion to airbnb/synapse


Nerve is a utility for tracking the status of machines and services.
It runs locally on the boxes which make up a distributed system, and reports state information to a distributed key-value store.
At Airbnb, we use Zookeeper as our key-value store.
The combination of Nerve and [Synapse](https://github.com/airbnb/synapse) make service discovery in the cloud easy!
