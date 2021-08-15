---
title: MAX-Image-Resolution-Enhancer
categories: ['python', 'computer-vision', 'machine-learning']
---
## [MAX-Image-Resolution-Enhancer](https://github.com/IBM/MAX-Image-Resolution-Enhancer)

### Upscale an image by a factor of 4, while generating photo-realistic details.


This repository contains code to instantiate and deploy an image resolution enhancer. 
This model is able to upscale a pixelated image by a factor of 4, while generating photo-realistic details.

The GAN is based on [this GitHub repository](https://github.com/brade31919/SRGAN-tensorflow) and on [this research article](https://arxiv.org/pdf/1609.04802.pdf).

The model was trained on 600,000 images of the [OpenImages V4](https://storage.googleapis.com/openimages/web/index.html) dataset, and the model files are hosted on
[IBM Cloud Object Storage](https://max-cdn.cdn.appdomain.cloud/max-image-resolution-enhancer/1.0.0/assets.tar.gz).
The code in this repository deploys the model as a web service in a Docker container. This repository was developed
as part of the [IBM Developer Model Asset Exchange](https://developer.ibm.com/exchanges/models/) and the public API is powered by [IBM Cloud](https://ibm.biz/Bdz2XM).
