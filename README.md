# Credit_Risk_Analysis
## Overview 
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
## Results
- Random Oversampling A 65.4%, P 0.99, R=0.59, F1= 0.72
- SMOTE Oversampling  A 66.2%, P 0.99, R 0.69, F1=0.81
-Undersampling A 66.2%, P 0.99, R 0.4, F1 0.56
-Combined A
-Balanced Random Forest A 78.76%, P .99, R 0.91
-EasyEnsemble A 91.9%, P 0.99, R 0.94, F1 0.97 

## Summary 
Based on the results the recommendation is to use Easy Ensemble Model

