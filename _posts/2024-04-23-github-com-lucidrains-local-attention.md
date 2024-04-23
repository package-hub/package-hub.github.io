---
title: local-attention
categories: ['python', 'artificial-intelligence', 'attention-mechanisms']
---
## [local-attention](https://github.com/lucidrains/local-attention)

### An implementation of local windowed attention for language modeling


An implementation of local windowed attention, which sets an incredibly strong baseline for language modeling. It is becoming apparent that a transformer needs local attention in the bottom layers, with the top layers reserved for global attention to integrate the findings of previous layers. This repository makes it easy to immediately employ local window attention.

This code has been battletested in multiple repositories already, alongside different implementations of sparse long-range attention.
