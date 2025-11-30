---
title: Boruta-Shap
categories: ['python']
---
## [Boruta-Shap](https://github.com/Ekeany/Boruta-Shap)

### A Tree based feature selection tool which combines both the Boruta feature selection algorithm with shapley values.  

BorutaShap is a wrapper feature selection method which combines both the Boruta feature selection algorithm with shapley values. This combination has proven to out perform the original Permutation Importance method in both speed, and the quality of the feature subset produced. Not only does this algorithm provide a better subset of features, but it can also simultaneously provide the most accurate and consistent global feature rankings which can be used for model inference too. Unlike the orginal R package, which limits the user to a Random Forest model, BorutaShap allows the user to choose any Tree Based learner as the base model in the feature selection process.

Despite BorutaShap's runtime improvements the SHAP TreeExplainer scales linearly with the number of observations making it's use cumbersome for large datasets. To combat this, BorutaShap includes a sampling procedure which uses the smallest possible subsample of the data availble at each iteration of the algorithm. It finds this sample by comparing the distributions produced by an isolation forest of the sample and the data using ks-test. From experiments, this procedure can reduce the run time up to 80% while still creating a valid approximation of the entire data set. Even with these improvments the user still might want a faster solution so BorutaShap has included an option to use the mean decrease in gini impurity. This importance measure is independent of the size dataset as it uses the tree's structure to compute a global feature ranking making it much faster than SHAP at larger datasets. Although this metric returns somewhat comparable feature subsets, it is not a reliable measure of global feature importance in spite of it's wide spread use. Thus, I would recommend to using the SHAP metric whenever possible.
