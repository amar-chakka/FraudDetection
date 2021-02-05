# FraudDetection
FraudDetection using Ensemble Learning

# Fraud Detection

![enter image description here](https://github.com/amar-chakka/FraudDetection/blob/main/download%20(1).jpg?raw=true)


This project was created as a part of the INSAID Term project to help customer in detecting credit card Fraud by analysing the transactions.  The data was sources from the kaggle.

In this project the outcome is a classification of Fraud or not. 

We are going to look at a Data set which contains 30 independent variables [float type] & 1 Target variable [int type].

Most of the features have  anonymous data except Time , Amount and Class.

All features V1 thru V28 are already scaled for the sake of anonymity.

75% of Amount have <=  $ 78 while 50% and 25% of Amount records  have  <=  $ 22 and  $ 6

Class is a Target variable. Its imbalanced with No Fraud [0 type] having 248315 [99.83%] & Fraud [1 type] having 492 [0.17%] records of the dataset.


tried with different classifiers for raw data and over sampled data.

◦Decision Tree Classifier

◦Logistic Regression Classifier

◦KNN Classifier

◦Random Forest Classifier

◦Voting Classifier

◦Bagging Classifier


To check out my notebook, please click [here](https://github.com/amar-chakka/FraudDetection/blob/main/FraudDetection_EnsembleLearning.ipynb).
