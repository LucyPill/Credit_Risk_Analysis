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

### Summary for Deliverable 1:
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

### Summary for Deliverable 2:
The recall scores of 64% for low risk and 60% for high risk loans are correctly identified.
Sam eas the previous model, the precision scores tell us that only 1% of high risk loans are correctly identified as high risk, but low risk loans are predicted correctly 100% of the time.

