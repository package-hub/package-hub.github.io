---
title: Torch-Pruning
categories: ['python', 'pytorch', 'pruning']
---
## [Torch-Pruning](https://github.com/VainF/Torch-Pruning)

### Structural Pruning for Model Acceleration

* Channel pruning for [CNNs](tests/test_torchvision_models.py) (e.g. ResNet, DenseNet, Deeplab) and [Transformers](tests/test_torchvision_models.py) (e.g. ViT)
* High-level pruners: MagnitudePruner, BNScalePruner, GroupPruner, etc.
* Graph Tracing and dependency fixing.
* Supported modules: Conv, Linear, BatchNorm, LayerNorm, Transposed Conv, PReLU, Embedding, MultiheadAttention, nn.Parameters and [customized modules](tests/test_customized_layer.py).
* Supported operations: split, concatenation, skip connection, flatten, etc.
* Pruning strategies: Random, L1, L2, etc.
* Low-level pruning [functions](torch_pruning/prune/structured.py)
* [Benchmarks](benchmarks) and [tutorials](tutorials)
