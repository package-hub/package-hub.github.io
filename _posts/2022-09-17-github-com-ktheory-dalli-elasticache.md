---
title: dalli-elasticache
categories: ['ruby']
---
## [dalli-elasticache](https://github.com/ktheory/dalli-elasticache)

### A wrapper for Dalli with support for AWS ElastiCache


The most common use of Dalli in Rails is to support a cache store.  To set up your cache store with a cluster, you'll need to generate the list of servers with Dalli ElastiCache and pass them to the `cache_store` configuration.  This needs to be done in your `config/environments/RAILS_ENV.rb` file for each Rails environment where you want to use a cluster.

```ruby
# in config/environments/production.rb
endpoint    = "my-cluster-name.abc123.cfg.use1.cache.amazonaws.com:11211"
elasticache = Dalli::ElastiCache.new(endpoint)

config.cache_store = :mem_cache_store, elasticache.servers, { expires_in: 1.day }
```