---
title: xraft
categories: ['java', 'raft', 'distributed-systems']
---
## [xraft](https://github.com/xnnyygn/xraft)

### xnnyygn's raft implementation


A raft implementation of XnnYygn's.

I want to make something with netty framework, and I found raft. Raft is interesting. As the first distributed consensus algorithm I learnt, I read the paper and implemented almost all of the feature of raft including

* Leader election and log replication
* Membership change(one server change)
* Log compaction

All these feature are implemented in xraft-core. And the client interaction in raft, I thought, should be the feature of service based on xraft-core. Until now, I made a simple key value store based on xraft-core, called xraft-kvstore. It supports GET and SET command.
