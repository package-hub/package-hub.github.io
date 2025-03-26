---
title: self-critical.pytorch
categories: ['python', 'image-captioning']
---
## [self-critical.pytorch](https://github.com/ruotianluo/self-critical.pytorch)

### Unofficial pytorch implementation for Self-critical Sequence Training for Image Captioning. and others.


This is a codebase for image captioning research.

It supports:
- Self critical training from [Self-critical Sequence Training for Image Captioning](https://arxiv.org/abs/1612.00563)
- Bottom up feature from [ref](https://arxiv.org/abs/1707.07998).
- Test time ensemble
- Multi-GPU training. (DistributedDataParallel is now supported with the help of pytorch-lightning, see [ADVANCED.md](ADVANCED.md) for details)
- Transformer captioning model.

A simple demo colab notebook is available [here](https://colab.research.google.com/github/ruotianluo/ImageCaptioning.pytorch/blob/colab/notebooks/captioning_demo.ipynb)
