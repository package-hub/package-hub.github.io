---
title: magpie
categories: ['python', 'neural-network', 'nlp']
---
## [magpie](https://github.com/inspirehep/magpie)

### Deep neural network framework for multi-label text classification

```
>>> magpie = Magpie()
>>> magpie.init_word_vectors('/path/to/corpus', vec_dim=100)
>>> magpie.train('/path/to/corpus', ['label1', 'label2', 'label3'], epochs=3)
Training...
>>> magpie.predict_from_text('Well, that was quick!')
[('label1', 0.96), ('label3', 0.65), ('label2', 0.21)]
```

