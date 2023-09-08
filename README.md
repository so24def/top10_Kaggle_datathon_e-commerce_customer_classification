# Predicting the Customer Segments by using e-commerce data

__Problem type: Multiclass Classification__

Includes solution and jury presentation of [__BTK Akademi Datathon 2023__](https://www.kaggle.com/competitions/datathon2023). I attended the competition solo and ranked in top 10 by the jury's selection out of 359 competitors and 255 teams. 


## Solution
* A very detailed EDA phase followed by multiple pivot tables
* Feature engineering; extracting new numerical features, trying the experimental "Cluster feature" method and getting statistical features by cluster groups
* Feature selection with [Sequential Feature Selection](https://rasbt.github.io/mlxtend/user_guide/feature_selection/SequentialFeatureSelector/), [RFECV](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFECV.html), [SHAP](https://shap.readthedocs.io/en/latest/) (not included in this repo)
* Model selection / model re-evaluation
* Detection and analysis of the sample that is being misclassified by each of the Random Forest, XGBoost, CatBoost, LightGBM models
* Hyperparameter tuning with Optuna
* Creating the final submission with decided final feature set and model architecture

***
* I also included every helper function that I use throughout different sections of the solution
***

#### External Data/Sources

* About the experimental "cluster feature" method: [1](http://scholar.googleusercontent.com/scholar?q=cache%3AjGchW-3Xsj0J%3Ascholar.google.com%2F&hl=tr&as_sdt=0%2C5&as_vis=1&scioq=Combining+Clustering+with+Classification%3A+A+Technique+to+Improve+Classification+Accuracy), [2](https://beei.org/index.php/EEI/article/view/1272)
* [SHAP implementation for multiclass classification](https://towardsdatascience.com/explainable-ai-xai-with-shap-multi-class-classification-problem-64dd30f97cea)


***

https://www.kaggle.com/so24def


