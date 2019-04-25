# Bank_Marketing_Campaign

## Introduction
Definition of Input Variables

    age - Age of the client- (numeric)

    job - Client’s occupation - (categorical) (admin, bluecollar, entrepreneur, housemaid, management, retired, selfemployed, services, student, technician, unemployed, unknown)

    marital - Client’s marital status - (categorical) (divorced, married, single, unknown, note: divorced means divorced or widowed)

    education - Client’s education level - (categorical) (basic.4y, basic.6y, basic.9y, high.school, illiterate, professional.course, university.degree, unknown)

    default - Indicates if the client has credit in default - (categorical) (no, yes, unknown)

    housing - Does the client as a housing loan? - (categorical) (no, yes, unknown)

    loan - Does the client as a personal loan? - (categorical) (no, yes, unknown’)

    contact - Type of communication contact - (categorical) (cellular, telephone)

    month - Month of last contact with client - (categorical) (January - December)

    day_of_week - Day of last contact with client - (categorical) (Monday - Friday)

    duration - Duration of last contact with client, in seconds - (numeric)

    campaign - Number of client contacts during this campaign - (numeric) (includes last contact)

    pdays - Number of days from last contacted from a previous campaign - (numeric) (999 means client was not previously contacted)

    previous - Number of client contacts performed before this campaign - (numeric)

    poutcome - Previous marketing campaign outcome - (categorical) (failure, nonexistent , success)

    emp.var.rate - Quarterly employment variation rate - (numeric)

    cons.price.idx - Monthly consumer price index - (numeric)

    cons.conf.idx - Monthly consumer confidence index - (numeric)

    euribor3m - Daily euribor 3 month rate - (numeric)

    nr.employed - Quarterly number of employees - (numeric)

    Output variable (desired target) - Term Deposit - subscription verified (binary: ‘yes’,‘no’)



* Baseline model:This notebook has a baseline model for the given dataset achieving an ROC_AUC score of 0.71 using a Logistic Regression model.
* Improvement 1: AUC_ROC = 0.8767(using a threshold of 0.5; AUC_ROC increases to 0.92 with model.predict_proba() i.e. when no threshold is applied) , Recall = 0.8934 on the test set (feature scaling, outlier removal is yet to be performed). 
*The solution can be improved further by some feature engineering and using ensembles instead of single classifiers.*
