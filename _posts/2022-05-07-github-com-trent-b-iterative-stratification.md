---
title: iterative-stratification
categories: ['python', 'multilabel', 'stratification']
---
## [iterative-stratification](https://github.com/trent-b/iterative-stratification)

### scikit-learn cross validators for iterative stratification of multilabel data

iterative-stratification is a project that provides [scikit-learn](http://scikit-learn.org/) compatible cross validators with stratification for multilabel data.

Presently scikit-learn provides several cross validators with stratification. However, these cross validators do not offer the ability to stratify _multilabel_ data. This iterative-stratification project offers implementations of MultilabelStratifiedKFold, MultilabelRepeatedStratifiedKFold, and MultilabelStratifiedShuffleSplit with a base algorithm for stratifying multilabel data described in the following paper:

Sechidis K., Tsoumakas G., Vlahavas I. (2011) On the Stratification of Multi-Label Data. In: Gunopulos D., Hofmann T., Malerba D., Vazirgiannis M. (eds) Machine Learning and Knowledge Discovery in Databases. ECML PKDD 2011. Lecture Notes in Computer Science, vol 6913. Springer, Berlin, Heidelberg.
