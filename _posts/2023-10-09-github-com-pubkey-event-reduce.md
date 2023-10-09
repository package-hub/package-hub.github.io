---
title: event-reduce
categories: ['typescript', 'realtime-queries', 'bdd']
---
## [event-reduce](https://github.com/pubkey/event-reduce)

### An algorithm to optimize database queries that run multiple times https://pubkey.github.io/event-reduce/


In the [browser demo](https://pubkey.github.io/event-reduce/) you can see that for randomly generated events, about **94%** of them could be optimized by EventReduce. In real world usage, with non-random events, this can be even higher. For the different implementations in common browser databases, we can observe an up to **12 times** faster displaying of new query results after a write occurred.
