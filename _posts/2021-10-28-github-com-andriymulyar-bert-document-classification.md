---
title: bert_document_classification
categories: ['python']
---
## [bert_document_classification](https://github.com/AndriyMulyar/bert_document_classification)

### architectures and pre-trained models for long document classification.

an easy-to-use interface to fully trained BERT based models for multi-class and multi-label long document classification.

pre-trained models are currently available for two clinical note (EHR) phenotyping tasks: smoker identification and obesity detection.

To sustain future development and improvements, we interface [pytorch-transformers](https://github.com/huggingface/pytorch-transformers)
for all language model components of our architectures. Additionally, their is a [blog post](http://andriymulyar.com/blog/bert-document-classification) describing the idea behind the architecture.

*This repository contains an updated implementation that corrects an error found in the original version of the preprint*
