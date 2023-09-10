---
title: tomcat-cluster-redis-session-manager
categories: ['java', 'tomcat-clustering', 'tomcat-session-manager']
---
## [tomcat-cluster-redis-session-manager](https://github.com/ran-jit/tomcat-cluster-redis-session-manager)

### Tomcat clustering redis session manager java client.


The Redis session manager is pluggable one. It stores session into Redis for easy distribution of HTTP Requests across a cluster of Tomcat servers.

Here the Sessions are implemented as non-sticky (means, each request can able to go to any server in the cluster, unlike the Apache provided Tomcat clustering setup.)

Request Sessions will be stored into Redis immediately (Session attributes must be Serializable), for the use of other servers. When tomcat receives a request from the client, Sessions are loaded directly from Redis.

Supports Redis default, sentinel and cluster mode, based on the configuration.

Going forward, we no need to enable sticky session (JSESSIONID) in Load Balancer.
