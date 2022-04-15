---
title: elasticsearch-prometheus-exporter
categories: ['java', 'elasticsearch', 'plugin']
---
## [elasticsearch-prometheus-exporter](https://github.com/vvanholl/elasticsearch-prometheus-exporter)

### Prometheus exporter plugin for Elasticsearch


This is a builtin exporter from Elasticsearch to Prometheus.
It collects all relevant metrics and makes them available to Prometheus via the Elasticsearch REST API.

**Currently, the available metrics are:**

- Cluster status
- Nodes status:
    - JVM
    - Indices (global)
    - Transport
    - HTTP
    - Scripts
    - Process
    - Operating System
    - File System
    - Circuit Breaker
- Indices status
- Cluster settings (selected [disk allocation settings](https://www.elastic.co/guide/en/elasticsearch/reference/master/disk-allocator.html) only)
