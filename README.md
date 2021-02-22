# Credit_Risk_Analysis

## Overview 

We're attempting to mitigate the classification imbalance in credit risk analysis by applying a number of sampling models to our data and measuring the results. The sampling methods we're employing: 1. oversampling the data with RandomOverSampler and SMOTE algorithms, 2. undersampling the data with the ClusterCentroids algorithm, 3. a combination of oversampling and undersampling using the SMOTEENN algorithm. After our resampling efforts are complete, we will compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 
