---
title: eland
categories: ['python', 'elasticsearch', 'pandas']
---
## [eland](https://github.com/elastic/eland)

### Python Client and Toolkit for DataFrames, Big Data, Machine Learning and ETL in Elasticsearch


Eland is a Python Elasticsearch client for exploring and
analyzing data in Elasticsearch with a familiar Pandas-compatible API.

Where possible the package uses existing Python APIs and data structures to make it easy to switch between numpy,
pandas, scikit-learn to their Elasticsearch powered equivalents. In general, the data resides in Elasticsearch and
not in memory, which allows Eland to access large datasets stored in Elasticsearch.

Eland also provides tools to upload trained machine learning models from your
common libraries like [scikit-learn](https://scikit-learn.org), [XGBoost](https://xgboost.readthedocs.io),
and [LightGBM](https://lightgbm.readthedocs.io) into Elasticsearch.
