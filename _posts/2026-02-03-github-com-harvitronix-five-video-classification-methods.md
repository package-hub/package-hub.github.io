---
title: five-video-classification-methods
categories: ['python', 'machine-learning', 'deep-learning']
---
## [five-video-classification-methods](https://github.com/harvitronix/five-video-classification-methods)

### Code that accompanies my blog post outlining five video classification methods in Keras and TensorFlow


The five video classification methods:

1. Classify one frame at a time with a ConvNet
1. Extract features from each frame with a ConvNet, passing the sequence to an RNN, in a separate network
1. Use a time-dstirbuted ConvNet, passing the features to an RNN, much like #2 but all in one network (this is the `lrcn` network in the code).
1. Extract features from each frame with a ConvNet and pass the sequence to an MLP
1. Use a 3D convolutional network (has two versions of 3d conv to choose from)

See the accompanying blog post for full details: https://medium.com/@harvitronix/five-video-classification-methods-implemented-in-keras-and-tensorflow-99cad29cc0b5
