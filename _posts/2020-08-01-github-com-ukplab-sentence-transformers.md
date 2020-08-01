---
title: sentence-transformers
categories: ['python']
---
## [sentence-transformers](https://github.com/UKPLab/sentence-transformers)

### Sentence Embeddings with BERT & XLNet

BERT / RoBERTa / XLM-RoBERTa produces out-of-the-box rather bad sentence embeddings. This repository fine-tunes BERT / RoBERTa / DistilBERT / ALBERT / XLNet with a siamese or triplet network structure to produce semantically meaningful sentence embeddings that can be used in unsupervised scenarios: Semantic textual similarity via cosine-similarity, clustering, semantic search.


We provide an increasing number of **state-of-the-art pretrained models** that can be used to derive sentence embeddings. See [Pretrained Models](#pretrained-models). Details of the implemented approaches can be found in our publication: [Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks](https://arxiv.org/abs/1908.10084) (EMNLP 2019).


You can use this code to easily **train your own sentence embeddings**, that are tuned for your specific task. We provide various dataset readers and you can tune sentence embeddings with different loss function, depending on the structure of your dataset. For further details, see [Train your own Sentence Embeddings](#Training).


