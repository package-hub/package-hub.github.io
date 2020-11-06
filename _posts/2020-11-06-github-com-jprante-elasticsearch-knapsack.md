---
title: elasticsearch-knapsack
categories: ['java']
---
## [elasticsearch-knapsack](https://github.com/jprante/elasticsearch-knapsack)

### Knapsack plugin is an import/export tool for Elasticsearch


Knapsack is an "swiss knife" export/import plugin for [Elasticsearch](http://github.com/elasticsearch/elasticsearch).
It uses archive formats (tar, zip, cpio) and also Elasticsearch bulk format with 
compression algorithms (gzip, bzip2, lzf, xz).

A pull or push of indexes or search hits with stored fields across clusters is also supported.

The knapsack actions can be executed via HTTP REST, or in Java using the Java API.

In archive files, the following index information is encoded:

- index settings
- index mappings
- index aliases

When importing archive files again, this information is reapplied.
