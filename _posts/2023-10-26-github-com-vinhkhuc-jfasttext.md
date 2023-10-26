---
title: JFastText
categories: ['java', 'machine-learning', 'nlp']
---
## [JFastText](https://github.com/vinhkhuc/JFastText)

### Java interface for fastText

JFastText is a Java wrapper for Facebook's [fastText](https://github.com/facebookresearch/fastText), 
a library for efficient learning of word embeddings and fast sentence classification. The JNI interface
is built using [javacpp](https://github.com/bytedeco/javacpp).

The library provides full fastText's command line interface. It also provides the API for
loading trained model from file to do label prediction in memory. Model training and quantization
are supported via the command line interface.

JFastText is ideal for building fast text classifiers in Java.
