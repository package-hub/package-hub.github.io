---
title: PGPortfolio
categories: ['python']
---
## [PGPortfolio](https://github.com/ZhengyaoJiang/PGPortfolio)

### PGPortfolio: Policy Gradient Portfolio, the source code of "A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem"(https://arxiv.org/pdf/1706.10059.pdf).

Note that this library is a part of our main project, and it is several versions ahead of the article.

* In this version, some technical bugs are fixed and improvements in hyper-parameter tuning and engineering are made.
  * The most important bug in the arxiv v2 article is that the test time-span mentioned is about 30% shorter than the actual experiment. Thus the volumn-observation interval (for asset selection) overlapped with the backtest data in the paper.
* With new hyper-parameters, users can train the models with smaller time durations.(less than 30 mins)
* All updates will be incorporated into future versions of the paper.
* Original versioning history,  and internal discussions, including some in-code comments, are removed in this open-sourced edition. These contains our unimplemented ideas, some of which will very likely become the foundations of our future publications
