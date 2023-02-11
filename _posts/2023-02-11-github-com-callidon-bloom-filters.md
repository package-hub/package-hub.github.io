---
title: bloom-filters
categories: ['typescript', 'bloom-filter', 'probabilistic']
---
## [bloom-filters](https://github.com/Callidon/bloom-filters)

### JS implementation of probabilistic data structures: Bloom Filter (and its derived), HyperLogLog, Count-Min Sketch, Top-K and MinHash


JavaScript/TypeScript implementation of probabilistic data structures: Bloom Filter (and its derived), HyperLogLog, Count-Min Sketch, Top-K and MinHash.
**This package relies on [non-cryptographic hash functions](https://cyan4973.github.io/xxHash/)**.

📕[Online documentation](https://callidon.github.io/bloom-filters/)

**Keywords:** _bloom filter, cuckoo filter, KyperLogLog, MinHash, Top-K, probabilistic data-structures, XOR-Filter._

❗️**Compatibility**❗️

- Be carefull when migrating from a version to another.
- Bug fixes were introduced in `1.3.7` and from `1.3.9` to `2.0.0+` for hashing and indexing data. Then, you **must re-build completely your filters from start** to be compatible with the new versions.
- To keep the `breaking changes` rule of npm versions we will make now new `majored versions` since 1.3.9 whenever a modification is done on the hashing/indexing system or breaks the current API.
