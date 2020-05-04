---
title: efficientdet-pytorch
categories: ['python', 'efficientdet', 'efficientnet']
---
## [efficientdet-pytorch](https://github.com/rwightman/efficientdet-pytorch)

### A PyTorch impl of EfficientDet faithful to the original Google impl w/ ported weights


This is a work in progress PyTorch implementation of EfficientDet. 

It is based on the
* official Tensorflow implementation by [Mingxing Tan and the Google Brain team](https://github.com/google/automl)
* paper by Mingxing Tan, Ruoming Pang, Quoc V. Le [EfficientDet: Scalable and Efficient Object Detection](https://arxiv.org/abs/1911.09070) 

I am aware there are other PyTorch implementations. Their approach didn't fit well with my aim to replicate the Tensorflow models closely enough to allow weight ports while still maintaining a PyTorch feel and a high degree of flexibility for future additions. So, this is built from scratch and leverages my previous EfficientNet work.