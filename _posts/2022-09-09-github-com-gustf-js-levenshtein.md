---
title: js-levenshtein
categories: ['javascript', 'levenshtein', 'edit-distance']
---
## [js-levenshtein](https://github.com/gustf/js-levenshtein)

### The most efficient JS implementation calculating the Levenshtein distance, i.e. the difference between two strings.


A very efficient JS implementation calculating the Levenshtein distance, i.e. the difference between two strings.

Based on Wagner-Fischer dynamic programming algorithm, optimized for speed and memory
 - use a single distance vector instead of a matrix
 - loop unrolling on the outer loop
 - remove common prefixes/postfixes from the calculation
 - minimize the number of comparisons
 - always allocate a new distance vector in order to not leak memory
 