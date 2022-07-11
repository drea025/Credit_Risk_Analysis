# Credit_Risk_Analysis

## Overview
Using the credit card credit dataset from LendingClub, we used oversampling of the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we used undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias in order to predict credit risk. Lastly we evaluated the performance of these models to predict credit risk.

## Results
### Cluster Centroid Undersampling

* Accuracy Score: 51.3%
* Precision High Risk: 0%
* Precision Low Risk: 100%
* Recall High Risk: 61%
* Recall Low Risk: 42%



### Naive Random Oversampling
<img width="845" alt="Screen Shot 2022-07-10 at 11 05 37 PM" src="https://user-images.githubusercontent.com/100797549/178199130-d5faafe9-7b4d-4f89-a63d-104e482df806.png">
* Accuracy Score: 65%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 63%
* Recall Low Risk: 66%

### SMOTE Oversampling

* Accuracy Score: 65%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 64%
* Recall Low Risk: 65%
<img width="725" alt="Screen Shot 2022-07-10 at 11 14 11 PM" src="https://user-images.githubusercontent.com/100797549/178200204-acf29c81-f8a9-4e4a-a0dc-6fc480dc9243.png">


### Cluster Centroid Undersampling

* Accuracy Score: 52%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 61%
* Recall Low Risk: 45%
<img width="689" alt="Screen Shot 2022-07-10 at 11 19 19 PM" src="https://user-images.githubusercontent.com/100797549/178200826-6c76331b-042a-4c23-9b50-9bb22ba0b339.png">


### SMOTEENN Sampling

* Accuracy Score: 68.1%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 76%
* Recall Low Risk: 60%


### Balanced Random Forest Classifying

* Precision High Risk: 56%
* Precision Low Risk: 100%
* Recall High Risk: 30%
* Recall Low Risk: 100%
* Precision: The precision is low for High-risk loans and is high for Low-risk loans.

### Easy Ensemble Classifying

* Precision High Risk: 6%
* Precision Low Risk: 100%
* Recall High Risk: 91%
* Recall Low Risk: 94%

Balanaced Accuracy:0.9316600714093861
Precision: The precision is low for High-risk and is high for Low-risk loans.

## Summary

This analysis is trying to find the best model that can detect if a loan is high risk or not. Becasue of that, we need to find a model that lets the least amount of high risk loans pass through undetected. That correlating statistic for this is the recall rate for high risk. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the best machine learning model to choose for further credit card analysis.

