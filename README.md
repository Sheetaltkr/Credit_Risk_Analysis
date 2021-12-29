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

In this model both classes have similar recall score but vast difference in their precision score. The precision and recall score is better for Low Risk class over High Risk class. 

![Naive Random Oversampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/naive.png)

### 2) SMOTE Oversampling
- **Balanced accuracy score:** 63%
- **High Risk Precision score:** 0.01
- **High Risk Recall score:** 0.62

In this model shows similar results as the model above. The precision and recall score is better for Low Risk class over High Risk class. 

![SMOTE Oversampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/smote.png)

### 3) ClusterCentroids Undersampling
- **Balanced accuracy score:** 51%
- **High Risk Precision score:** 0.01
- **High Risk Recall score:** 0.59

In this model High Risk Class has better recall score over Low Risk Class. However there is vast difference in their precision scores. 


![ClusterCentroids Undersampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)

### 4) Combination (Over and Under) Sampling
- **Balanced accuracy score:** 64%
- **High Risk Precision score:** 0.01
- **High Risk Recall score:** 0.70

In this model High Risk Class has better recall score over Low Risk Class. However there is still vast difference in their precision scores.This shows better results over earlier 3 models.


![Combination (Over and Under) Sampling](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/smoteenn.png)

### 5) Balanced Random Forest Classifier
- **Balanced accuracy score:** 67%
- **High Risk Precision score:** 0.73
- **High Risk Recall score:** 0.34

Here High Risk Class's precision score and F1 score is highest among all models. However Low Risk class precision and recall scores are better.

![Balanced Random Forest Classifier](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/brfc.png)

### 6) Easy Ensemble AdaBoost Classifier

- **Balanced accuracy score:** 92.5%
- **High Risk Precision score:** 0.07
- **High Risk Recall score:** 0.91

This model has highest accuracy score among all models.However Low Risk class precision and recall scores are better over High Risk Class scores.


![Easy Ensemble AdaBoost Classifier](https://github.com/Sheetaltkr/Credit_Risk_Analysis/blob/main/Resources/eec.png)


### Summary: 

- The credit risk assessment dataset is a highly imbalanced dataset, the balanced accuracy score for such dataset might be misleading and hence the f1 score should be considered over accuracy score for evaluation of the prediction models.
- Also as we want all high Risk predictions to be predicted correctly and none of the high risk prediction should be flagged as Low Risk, the sensitivity score outweighs the precision score.
- Since the f1 score for High Risk Class for all the models is low even though the accuracy score is high for Easy Ensemble AdaBoost Classifier model, we could not come to conclusion if the tried algorithms can be used to make Credit Risk predictions.


