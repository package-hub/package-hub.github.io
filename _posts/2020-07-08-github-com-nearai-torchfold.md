---
title: torchfold
categories: ['python', 'machine-learning', 'deep-learning']
---
## [torchfold](https://github.com/nearai/torchfold)

### Tools for PyTorch


Blog post: http://near.ai/articles/2017-09-06-PyTorch-Dynamic-Batching/

Analogous to [TensorFlow Fold](https://github.com/tensorflow/fold), implements dynamic batching with super simple interface.
Replace every direct call in your computation to nn module with `f.add('function name', arguments)`.
It will construct an optimized version of computation and on `f.apply` will dynamically batch and execute the computation on given nn module.
