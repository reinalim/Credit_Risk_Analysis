# Credit_Risk_Analysis

## Overview
The purpose of this anlaysis is to predit credit card risk by analyzing the credit dataset from LendingClub, a peer-to-peer lending services company, using machine learning methods to better predit and assess card card risk.

# Results

The analysis is conducted by using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm, then using combinatorial approach of over and undersampling using the SMOTEENN algorithm. Finally, it involves using two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk.

 1. Naive Random Oversampling

 <img src=https://github.com/reinalim/Credit_Risk_Analysis/blob/main/NaiveRandomOversampling.png>
 
 * For high risk credit card applications, it resulted in a precision score of 1.00 and a recall score of 0.01.
 * For low risk credit card applications, it resulted in a precision score of 1.00 and a recall score of 1.00.
 * The random oversamping method resulted in a balanced accuracy score of: 0.11.
 
 2. SMOTE

  <img src=https://github.com/reinalim/Credit_Risk_Analysis/blob/main/SMOTEOversampling.png>
  
  * For high risk credit card applications, it resulted in a precision score of 0.01 and a recall score of 0.61.
  * For low risk credit card applications, it resulted in a precision score of 1.00 and a recall score of 0.69.
  * The SMOTE oversamping method resulted in a balanced accuracy score of 0.65.
  
 3. Combination (Over and Under)
 
 <img src=https://github.com/reinalim/Credit_Risk_Analysis/blob/main/Combination(OverandUnder).png>
 
  * For high risk credit card applications, it resulted in a precision score of 0.01 and a recall score of 0.70.
  * For low risk credit card applications, it resulted in a precision score of 1.00 and a recall score of 0.59.
  * The SMOTEENN method resulted in a balanced accuracy score of 0.64.


4. Balanced Random Forest

 <img src=https://github.com/reinalim/Credit_Risk_Analysis/blob/main/BalancedRandomClassifier.png>
 
 * For high risk credit card applications, it resulted in a precision score of 0.03 and a recall score of 0.70.
 * For low risk credit card applications, it resulted in a precision score of 1.00 and a recall score of 0.87.
 * The Balanced Random forest Classifier method resulted in a balanced accuracy score of 0.78.
 
5. Easy Ensemble Classifier

 <img src=https://github.com/reinalim/Credit_Risk_Analysis/blob/main/EasyEnsemble.png>
 
 * For high risk credit card applications, it resulted in a precision score of 0.09 and a recall score of 0.92.
 * For low risk credit card applications, it resulted in a precision score of 1.00 and a recall score of 0.94.
 * The Easy Ensemble Classifier method resulted in a balanced accuracy score of: 0.93.


6. Undersampling

 <img src=https://github.com/reinalim/Credit_Risk_Analysis/blob/main/Undersampling.png>
 
 * For high risk credit card applications, it resulted in a precision score of 0.01 and a recall score of 0.61.
 * For low risk credit card applications, it resulted in a precision score of 1.80 and a recall score of 0.45.
 * The Cluster Centroid method resulted in a balanced accuracy score of: 0.52.

# Summary
According to the analysis, the Easy Ensemable Classifier method demonstrates the highest balanced accuracy score of 0.93 compared to other medthods. Therefore, it is recommended to use the Easy Ensemable Classifier method to predit the credit card risk to increase accuracy of the predition and minimize the risk. 
