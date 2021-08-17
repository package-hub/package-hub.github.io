---
title: fancyimpute
categories: ['python']
---
## [fancyimpute](https://github.com/iskandr/fancyimpute)

### Multivariate imputation and matrix completion algorithms implemented in Python


(1) This project is in "bare maintenance" mode. That means we are not planning on adding more imputation algorithms or features (but might if we get inspired). Please do report bugs, and we'll try to fix them. Also, we are happy to take pull requests for more algorithms and/or features. 

(2) `IterativeImputer` started its life as a `fancyimpute` original, but was then merged into `scikit-learn` and we deleted it from `fancyimpute` in favor of the better-tested `sklearn` version. As a convenience, you can still `from fancyimpute import IterativeImputer`, but under the hood it's just doing `from sklearn.impute import IterativeImputer`.  That means if you update `scikit-learn` in the future, you may also change the behavior of `IterativeImputer`. 

