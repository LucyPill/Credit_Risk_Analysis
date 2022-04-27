# Credit_Risk_Analysis

## Overview/Purpose:
The purpose of this analysis is to use various machine learning models to predict credit card risk. We will resample the data and determine the model that better predict risk.

We will use:
* Random Oversampling 
* SMOTE
* ClusterCentroids
* SMOTEENN algorithms 
* Balanced Random Forest Classifier
* Easy Ensemble AdaBoost Classifier

## Results:
## Deliverable 1: Use Resampling Models to Predict Credit Risk

* For all three algorithms, the following have been completed:

#### 1. An accuracy score for the model is calculated
![1.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/1.png)

* The balanced accuracy score gives us an overall success rate of 64%.

#### 2. A confusion matrix has been generated

![3.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/3.png)

#### 3. An imbalanced classification report has been generated
##### Precision:
*  High risk: 0.01 / Low risk: 1.00
##### Recall: 
* High risk: 0.61 / Low risk: 0.68
* F1 Score: 0.80

![2.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/2.png)

## Summary for Deliverable 1:
The recall scores of 68% for low risk and 61% for high risk loans are correctly identified.
The precision scores tell us that only 1% of high risk loans are correctly identified as high risk, but low risk loans are predicted correctly 100% of the time.

## Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk

* The combinatorial SMOTEENN algorithm does the following:

#### 1. An accuracy score for the model is calculated
![4.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/4.png)

* The balanced accuracy score gives us an overall success rate of 62%. This is a bit lower than the prevoius model.

#### 2. A confusion matrix has been generated

![5.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/5.png)

#### 3. An imbalanced classification report has been generated
##### Precision:
*  High risk: 0.01 / Low risk: 1.00
##### Recall: 
* High risk: 0.60 / Low risk: 0.64
* F1 Score: 0.78

![6.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/6.png)

## Summary for Deliverable 2:
The recall scores of 64% for low risk and 60% for high risk loans are correctly identified.
Sam eas the previous model, the precision scores tell us that only 1% of high risk loans are correctly identified as high risk, but low risk loans are predicted correctly 100% of the time.


## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

#### Part 1: The BalancedRandomForestClassifier algorithm does the following

#### 1. An accuracy score for the model is calculated
![7.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/7.png)

* The balanced accuracy score gives us an overall success rate of 78.77%. This is a bit lower than the prevoius model.

#### 2. A confusion matrix has been generated

![8.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/8.png)

#### 3. An imbalanced classification report has been generated
##### Precision:
*  High risk: 0.04 / Low risk: 1.00
##### Recall: 
* High risk: 0.67 / Low risk: 0.91
* F1 Score: 0.95

![9.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/9.png)

## Summary for Deliverable 3 - Part 1:
The recall scores of 91% for low risk and 67% for high risk loans are correctly identified.
The precision scores tell us that only 4% of high risk loans are correctly identified as high risk, but low risk loans are predicted correctly 100% of the time.

## Deliverable 3: Part 2 
### The EasyEnsembleClassifier algorithm does the following

#### 1. An accuracy score for the model is calculated

The accuracy score gives us they highest success rate 93%. This is a high rate of prediction which means this model 93% of the times predicts correctly whether a loan is high or low risk.

![11.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/11.png)

#### 2. A confusion matrix has been generated

![12.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/12.png)

#### 3. An imbalanced classification report has been generated
##### Precision:
*  High risk: 0.07 / Low risk: 1.00
##### Recall: 
* High risk: 0.91 / Low risk: 0.94
* F1 Score: 0.97

![13.png](https://github.com/LucyPill/Credit_Risk_Analysis/blob/main/images/13.png)

## Summary for Deliverable 3 - Part 2:
The recall scores of 94% for low risk and 91% for high risk loans are correctly identified.
The precision scores tell us that only 7% of high risk loans are correctly identified as high risk, but low risk loans are predicted correctly 100% of the time.

## Overall Summary:
Out of these models, the algorithm with the highest rate of precision was the Easy Ensemble AdaBoost Classifier which identifies high risk loans correctly 7% of the time. The Easy Ensemble Classifier is also the most sensitive of the models with a recall rate of 94%, meaning that 94% of the high risk loans were correctly predicted.
