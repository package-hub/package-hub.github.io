---
title: logstash-output-amazon_es
categories: ['ruby']
---
## [logstash-output-amazon_es](https://github.com/awslabs/logstash-output-amazon_es)

### Logstash output plugin to sign and export logstash events to Amazon Elasticsearch Service



This plugin is now in maintenance mode. We will supply bug fixes and security patches for v7.2.X, older versions are no longer supported. This change is because the OpenSearch Project created a new Logstash output plugin
[logstash-output-opensearch](https://github.com/opensearch-project/logstash-output-opensearch) which ships events from
Logstash to OpenSearch 1.x and Elasticsearch 7.x clusters, and also supports SigV4 signing. Having similar functionality
plugins can be redundant, so we plan to eventually replace this logstash-output-amazon_es plugin with the logstash-output-opensearch
plugin.

To help you migrate to [logstash-output-opensearch](https://github.com/opensearch-project/logstash-output-opensearch) plugin, please
find below a brief migration guide.
