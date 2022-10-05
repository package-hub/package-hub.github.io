---
title: torchlayers
categories: ['python', 'pytorch', 'inference']
---
## [torchlayers](https://github.com/szymonmaszke/torchlayers)

### Shape and dimension inference (Keras-like) for PyTorch layers and neural networks


* __Shape inference__ for most of `torch.nn` module (__convolutional, recurrent, transformer, attention and linear layers__)
* __Dimensionality inference__ (e.g. `torchlayers.Conv` working as `torch.nn.Conv1d/2d/3d` based on `input shape`)
* __Shape inference of custom modules__ (see examples section)
* __Additional [Keras-like](https://www.tensorflow.org/guide/keras) layers__ (e.g. `torchlayers.Reshape` or `torchlayers.StandardNormalNoise`)
* __Additional SOTA layers__ mostly from ImageNet competitions
(e.g. [PolyNet](https://arxiv.org/abs/1608.06993),
[Squeeze-And-Excitation](https://arxiv.org/abs/1709.01507),
[StochasticDepth](www.arxiv.org/abs/1512.03385>))
* __Useful defaults__ (`"same"` padding and default `kernel_size=3` for `Conv`, dropout rates etc.)
* __Zero overhead and [torchscript](https://pytorch.org/docs/stable/jit.html) support__

__Keep in mind this library works almost exactly like PyTorch originally__.
What that means is you can use `Sequential`, __define your own networks of any complexity using
`torch.nn.Module`__, create new layers with shape inference etc.

_See below to get some intuition about library_.
