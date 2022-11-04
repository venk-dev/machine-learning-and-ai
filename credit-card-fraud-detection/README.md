# Fraud Detection using Machine Learning

Credit card frauds happen on a regular basis. There exists a wide variety of scenarios that may lead a fraudster to successfully perform fraudulent payments with a credit card. There is currently no definite taxonomy on credit card fraud types, though certain patterns are known to occur more frequently than others. Different payment/transaction types could be credit card, mobile wallet, person-to-person transfers, authentication.

## Research Question

Find a good machine learning model which can identify fraudulent transactions effectively with a good score and overall good metrics. It should be deployable in the cloud environment like AWS such that the model effectively can be applied to the real world business application or a product.

## Dataset

The dataset is obtained from https://www.kaggle.com/datasets/mlg-ulb/creditcardfraudLinks to an external site. . The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Project Description

The project uses different algorithms as below. For second part of the prediction, the data is balanced using SMOTE.
* Logistic Regression
* Random Forest
* XGBoost
* Ada Boost

Metrics used:
* Accuracy
* Precision
* F1-Score
* Recall
* AUC/RUC Curve

The project also uses the algorith IsolationForest for anomaly detection.


## Contents

* `notebooks/`
  * `Fraud_Detection_Using_Machine_Learning.ipynb`: Credit card fraud detection using different machine learning algorithms.
