---
title: webcam-pix2pix-tensorflow
categories: ['python']
---
## [webcam-pix2pix-tensorflow](https://github.com/memo/webcam-pix2pix-tensorflow)

### Source code and pretrained model for webcam pix2pix

The code in this particular repo actually has nothing to do with pix2pix, GANs or even deep learning. It just loads *any* pre-trained tensorflow model (as long as it complies with a few constraints), feeds it a processed webcam input, and displays the output of the model. It just so happens that the model I trained and used is pix2pix (details below). 

I.e. The steps can be summarised as:

1. Collect data: scrape the web for a ton of images, preprocess and prepare training data
2. Train and export a model
3. Preprocessing and prediction: load pretrained model, feed it live preprocessed webcam input, display the results. 
