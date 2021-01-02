---
title: lmdb-embeddings
categories: ['python', 'word', 'vectors']
---
## [lmdb-embeddings](https://github.com/ThoughtRiver/lmdb-embeddings)

### Fast word vectors with little memory usage in Python

Query word vectors (embeddings) very quickly with very little querying time overhead and far less memory usage than gensim or other equivalent solutions. This is made possible by [Lightning Memory-Mapped Database](https://en.wikipedia.org/wiki/Lightning_Memory-Mapped_Database).

Inspired by [Delft](https://github.com/kermitt2/delft). As explained in their readme, this approach permits us to have the pre-trained embeddings immediately "warm" (no load time), to free memory and to use any number of embeddings similtaneously with a very negligible impact on runtime when using SSD.

For instance, in a traditional approach `glove-840B` takes around 2 minutes to load and 4GB in memory. Managed with LMDB, `glove-840B` can be accessed immediately and takes only a couple MB in memory, for a negligible impact on runtime (around 1% slower).
