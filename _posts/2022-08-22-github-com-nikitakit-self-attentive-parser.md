---
title: self-attentive-parser
categories: ['python', 'nlp', 'natural-language-processing']
---
## [self-attentive-parser](https://github.com/nikitakit/self-attentive-parser)

### High-accuracy NLP parser with models for 11 languages.


A high-accuracy parser with models for 11 languages, implemented in Python. Based on [Constituency Parsing with a Self-Attentive Encoder](https://arxiv.org/abs/1805.01052) from ACL 2018, with additional changes described in [Multilingual Constituency Parsing with Self-Attention and Pre-Training](https://arxiv.org/abs/1812.11760).

**New February 2021:** Version 0.2.0 of the Berkeley Neural Parser is now out, with higher-quality pre-trained models for all languages. Inference now uses PyTorch instead of TensorFlow (training has always been PyTorch-only). Drops support for Python 2.7 and 3.5. Includes updated support for training and using your own parsers, based on your choice of [pre-trained model](https://huggingface.co/models).
