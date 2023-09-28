---
title: gensim-data
categories: ['python', 'dataset', 'gensim']
---
## [gensim-data](https://github.com/RaRe-Technologies/gensim-data)

### Data repository for pretrained NLP models and NLP corpora.


Research datasets regularly disappear, change over time, become obsolete or come without a sane implementation to handle the data format reading and processing.

For this reason, [Gensim](https://github.com/RaRe-Technologies/gensim) launched its own dataset storage, committed to long-term support, a sane standardized usage API and focused on datasets for **unstructured text processing** (no images or audio). This [Gensim-data](https://github.com/RaRe-Technologies/gensim-data) repository serves as that storage.

**There's no need for you to use this repository directly**. Instead, simply install Gensim and use its download API (see the Quickstart below). It will "talk" to this repository automagically.

💡 When you use the Gensim download API, all data is stored in your `~/gensim-data` home folder.

Read more about the project rationale and design decisions in this article: [New Download API for Pretrained NLP Models and Datasets](https://rare-technologies.com/new-download-api-for-pretrained-nlp-models-and-datasets-in-gensim/).
