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

### Naive Random Oversampling
- **Balanced accuracy score:**
- **Precision score:**
- **Recall score:**


![Naive Random Oversampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/naive.png)

### SMOTE Oversampling
- **Balanced accuracy score:**
- **Precision score:**
- **Recall score:**


![SMOTE Oversampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/smote.png)

### ClusterCentroids Undersampling
- **Balanced accuracy score:**
- **Precision score:**
- **Recall score:**


![ClusterCentroids Undersampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)

### Combination (Over and Under) Sampling
- **Balanced accuracy score:**
- **Precision score:**
- **Recall score:**


![Combination (Over and Under) Sampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/smoteenn.png)

### Balanced Random Forest Classifier
- **Balanced accuracy score:**
- **Precision score:**
- **Recall score:**


![Balanced Random Forest Classifier](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/brfc.png)

### Easy Ensemble AdaBoost Classifier

- **Balanced accuracy score:**
- **Precision score:**
- **Recall score:**

![Easy Ensemble AdaBoost Classifier](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/eec.png)


### Summary: 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
