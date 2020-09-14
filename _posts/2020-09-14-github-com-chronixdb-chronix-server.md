---
title: chronix.server
categories: ['java', 'chronix-server', 'time-series']
---
## [chronix.server](https://github.com/ChronixDB/chronix.server)

### The Chronix Server implementation that is based on Apache Solr.

The Chronix Server is an implementation of the Chronix API that stores time series in [Apache Solr](http://lucene.apache.org/solr/).
Chronix uses several techniques to optimize query times and storage demand.
Thus Chronix achieves on a benchmark asking serveral ranges (.5 day up to 180 days) an average runtime per range-query of 23 milliseconds.
The dataset contains about 3.7 billion pairs and takes 108 GB serialized as CSV.
Chronix needs only 8.7 GB to store the dataset.
Everything runs on a standard laptop computer.
No need of clustering, parallel processing or another complex stuff.
Check it out and give it a try.

The repository [chronix.examples](https://github.com/ChronixDB/chronix.examples) contains some examples.
