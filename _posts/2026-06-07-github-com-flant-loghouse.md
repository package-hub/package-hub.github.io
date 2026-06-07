---
title: loghouse
categories: ['ruby', 'kubernetes', 'clickhouse']
---
## [loghouse](https://github.com/flant/loghouse)

### Ready to use log management solution for Kubernetes storing data in ClickHouse and providing web UI.


* Collecting and storing logs from all Kubernetes pods efficiently:
  * [Fluentd](https://www.fluentd.org/) processes upto 10,000 log entries per second consuming 300 MB of RAM (installed at each K8s node).
  * ClickHouse makes disk space usage minimal. Examples of logs stored in our production deployments: 3.7 million entries require 1.2 GB, 300m — 13 GB, 5,35 billion — 54 GB.
* [Simple query language](docs/en/query-language.md): Easy to select entries by exact keys values or regular expressions, multiple conditions are supported with AND/OR. *Learn more in [query language docs](docs/en/query-language.md)*.
* Selecting entries based on additional containers' data available in Kubernetes API (pod's and container's names, host, namespace, labels, etc).
* Quickly & straightforward deployable to Kubernetes via Dockerfiles and Helm chart.
* Web UI made cosy and powerful:
  * Papertrail-like user experience.
  * Customizable time frames: from date to date / from now till given period (last hour, last day, etc) / seek to specific time and show logs around it.
  * Infinite scrolling of older log entries.
  * Save your queries to use in future.
  * Basic permissions (limiting entries shown for users by specifying Kubernetes namespaces).
  * Exporting current query's results to CSV (more formats will be supported).
* fluentd monitoring via Prometheus with Grafana dashboards for ClickHouse and fluentd.

