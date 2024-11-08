---
title: swin-transformer-pytorch
categories: ['python', 'deep-learning', 'machine-learning']
---
## [swin-transformer-pytorch](https://github.com/berniwal/swin-transformer-pytorch)

### Implementation of the Swin Transformer in PyTorch.


Implementation of the [Swin Transformer](https://arxiv.org/pdf/2103.14030.pdf) architecture. This paper presents a new vision Transformer, called Swin Transformer, that capably serves as a general-purpose backbone for computer vision. Challenges in adapting Transformer from language to vision arise from differences between the two domains, such as large variations in the scale of visual entities and the high resolution of pixels in images compared to words in text. To address these differences, we propose a hierarchical Transformer whose representation is computed with shifted windows. The shifted windowing scheme brings greater efficiency by limiting self-attention computation to non-overlapping local windows while also allowing for cross-window connection. This hierarchical architecture has the flexibility to model at various scales and has linear computational complexity with respect to image size. These qualities of Swin Transformer make it compatible with a broad range of vision tasks, including image classification (86.4 top-1 accuracy on ImageNet-1K) and dense prediction tasks such as object detection (58.7 box AP and 51.1 mask AP on COCO test-dev) and semantic segmentation (53.5 mIoU on ADE20K val). Its performance surpasses the previous state-of-the-art by a large margin of +2.7 box AP and +2.6 mask AP on COCO, and +3.2 mIoU on ADE20K, demonstrating the potential of Transformer-based models as vision backbones.

This is **NOT** the official repository of the Swin Transformer. At the moment in time the official code of the authors is not available yet but can be found later at: [https://github.com/microsoft/Swin-Transformer](https://github.com/microsoft/Swin-Transformer).

All credits go to the authors [Ze Liu](https://github.com/zeliu98/), [Yutong Lin](https://github.com/impiga), [Yue Cao](http://yue-cao.me), [Han Hu](https://sites.google.com/site/hanhushomepage/), [Yixuan Wei](https://github.com/weiyx16), [Zheng Zhang](https://stupidzz.github.io/), [Stephen Lin](https://scholar.google.com/citations?user=c3PYmxUAAAAJ&hl=en) and [Baining Guo](https://www.microsoft.com/en-us/research/people/bainguo/).