---
title: elasticsearch-learning-to-rank
categories: ['java', 'elasticsearch', 'relevant-search']
---
## [elasticsearch-learning-to-rank](https://github.com/o19s/elasticsearch-learning-to-rank)

### Plugin to integrate Learning to Rank (aka machine learning for better relevance) with Elasticsearch


This plugin:

- Allows you to store features (Elasticsearch query templates) in Elasticsearch
- Logs features scores (relevance scores) to create a training set for offline model development
- Stores linear, xgboost, or ranklib ranking models in Elasticsearch that use features you've stored
- Ranks search results using a stored model
