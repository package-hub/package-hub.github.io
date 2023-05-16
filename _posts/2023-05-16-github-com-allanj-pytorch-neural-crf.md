---
title: pytorch_neural_crf
categories: ['python']
---
## [pytorch_neural_crf](https://github.com/allanj/pytorch_neural_crf)

### Pytorch implementation of LSTM/BERT-CRF for named entity recognition


This repository implements an LSTM-CRF model for named entity recognition. The model is same as the one by [Lample et al., (2016)](http://www.anthology.aclweb.org/N/N16/N16-1030.pdf) except we do not have the last `tanh` layer after the BiLSTM.
We achieve the SOTA performance on both CoNLL-2003 and OntoNotes 5.0 English datasets (check our [benchmark](/docs/benchmark.md) with Glove and ELMo, other 
and [benchmark results](/docs/transformers_benchmark.md) with fine-tuning BERT). 

**Announcements**
* We implemented distributed training for faster training
* We implemented a [**Faster CRF**](/docs/fast_crf.md) module which allows **O(log N) inference and back-tracking**! 
* [Benchmark results](/docs/transformers_benchmark.md) by fine-tuning BERT/Roberta**


| Model| Dataset | Precision | Recall | F1 |
|-------| ------- | :---------: | :------: | :--: |
|BERT-base-cased + CRF (this repo)| CONLL-2003 | 91.69 | 92.05 | 91.87 |
|Roberta-base  + CRF (this repo)| CoNLL-2003 | **91.88**  | **93.01** |**92.44**|
|BERT-base-cased  + CRF (this repo)| OntoNotes 5 |89.57  | 89.45 | 89.51 |
|Roberta-base  + CRF (this repo)| OntoNotes 5 | **90.12**  | **91.25** |**90.68**|

More [details](/docs/transformers_benchmark.md)
