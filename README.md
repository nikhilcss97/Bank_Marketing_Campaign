# Bank_Marketing_Campaign
Baseline model:This notebook has a baseline model for the given dataset achieving an ROC_AUC score of 0.71 using a Logistic Regression model.
Improvement 1: AUC_ROC = 0.8767(using a threshold of 0.5; AUC_ROC increases to 0.92 with model.predict_proba() i.e. when no threshold is applied) , Recall = 0.8934 on the test set (feature scaling, outlier removal is yet to be performed). The solution can be improved further by some feature engineering and using ensembles instead of single classifiers.
