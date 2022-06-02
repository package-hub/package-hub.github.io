---
title: loss-landscapes
categories: ['python']
---
## [loss-landscapes](https://github.com/marcellodebernardi/loss-landscapes)

### Approximating neural network loss landscapes in low-dimensional parameter subspaces for PyTorch


`loss-landscapes` is a PyTorch library for approximating neural network loss functions, and other related metrics, 
in low-dimensional subspaces of the model's parameter space. The library makes the production of visualizations
such as those seen in [Visualizing the Loss Landscape of Neural Nets](https://arxiv.org/abs/1712.09913v3) much
easier, aiding the analysis of the geometry of neural network loss landscapes.

This library does not provide plotting facilities, letting the user define how the data should be plotted. Other
deep learning frameworks are not supported, though a TensorFlow version, `loss-landscapes-tf`, is planned for
a future release.

**NOTE: this library is in early development. Bugs are virtually a certainty, and the API is volatile. Do not use
this library in production code. For prototyping and research, always use the newest version of the library.**

