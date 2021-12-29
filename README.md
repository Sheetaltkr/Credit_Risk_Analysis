# Credit_Risk_Analysis

## Overview of the analysis: 

### Purpose

- Perform Credit Risk Analysis by building and evaluating several machine learning models or algorithms for Fast lending, a peer to peer lending services company. The dataset to     be used is credit card credit dataset from LendingClub.
  The Tasks to be accomplished are:
    - Oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm.
    - Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.

- Compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk
- Evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Resources
Data Source: LoanStats_2019Q1.csv
Software: Python 3.7.11, Conda 4.11, Jupyter Notebook 6.4.6

## Results: 

### 1) Naive Random Oversampling
- **Balanced accuracy score:** 66%
- **High Risk Precision score:** 0.01
- **High Risk Recall score:** 0.66


![Naive Random Oversampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/naive.png)

### 2) SMOTE Oversampling
- **Balanced accuracy score:** 63%
- **High Risk Precision score:** 0.01
- **High Risk Recall score:** 0.62


![SMOTE Oversampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/smote.png)

### 3) ClusterCentroids Undersampling
- **Balanced accuracy score:** 51%
- **High Risk Precision score:** 0.01
- **High Risk Recall score:** 0.59
- **Low Risk Precision score:** 1.00
- **Low Risk Recall score:** 0.64


![ClusterCentroids Undersampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)

### 4) Combination (Over and Under) Sampling
- **Balanced accuracy score:** 64%
- **High Risk Precision score:** 0.01
- **High Risk Recall score:** 0.70


![Combination (Over and Under) Sampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/smoteenn.png)

### 5) Balanced Random Forest Classifier
- **Balanced accuracy score:** 67%
- **High Risk Precision score:** 0.73
- **High Risk Recall score:** 0.34


![Balanced Random Forest Classifier](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/brfc.png)

### 6) Easy Ensemble AdaBoost Classifier

- **Balanced accuracy score:** 92.5%
- **High Risk Precision score:** 0.07
- **High Risk Recall score:** 0.91

![Easy Ensemble AdaBoost Classifier](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/eec.png)


### Summary: 


