---
title: dl-on-flink
categories: ['java', 'flink', 'tensorflow']
---
## [dl-on-flink](https://github.com/flink-extended/dl-on-flink)

### Deep Learning on Flink aims to integrate Flink and deep learning frameworks (e.g. TensorFlow, PyTorch, etc) to enable distributed deep learning training and inference on a Flink cluster.


Deep Learning on Flink aims to integrate Flink and deep learning frameworks
(e.g. TensorFlow, PyTorch, etc.) to enable distributed deep learning training and
inference on a Flink cluster.

It runs the deep learning tasks inside a Flink operator so that Flink can help
establish a distributed environment, manage the resource, read/write the data
with the rich connectors in Flink and handle the failures.

Currently, Deep Learning on Flink supports TensorFlow.
