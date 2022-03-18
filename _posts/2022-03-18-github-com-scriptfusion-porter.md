---
title: Porter
categories: ['php', 'porter', 'data-import']
---
## [Porter](https://github.com/ScriptFUSION/Porter)

### :lipstick: Scalable and durable all-purpose data import abstraction for publishing testable APIs and SDKs.


Porter is the all-purpose PHP data importer. She fetches data from anywhere and serves it as a single record or an iterable [record collection](#record-collections), encouraging processing one record at a time instead of loading full data sets into memory at once. Her [durability](#durability) feature provides automatic, transparent recovery from intermittent network connectivity errors by default.

Porter's [interface trichotomy](#overview) of [providers](#providers), [resources](#resources) and [connectors](#connectors) maps well to APIs. For example, a typical API such as GitHub would define the provider as GitHub, a resource as `GetUser` or `ListRepositories` and the connector could be [HttpConnector][].

Porter provides a dual API for synchronous and [asynchronous](#asynchronous) imports, both of which are concurrency safe, so multiple imports can be paused and resumed simultaneously. Asynchronous mode allows large scale imports across multiple connections to work at maximum efficiency without waiting for each network call to complete.
