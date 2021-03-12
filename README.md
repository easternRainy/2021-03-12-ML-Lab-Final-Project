# Bank Churner Classifier
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/secregister01/2021-03-12-ML-Lab-Final-Project/]
This is Sicheng Zhou's final project of USFCA MSDS 699 Machine Learning Lab taught by professor [Brian Spiering](https://www.linkedin.com/in/brianspiering/).

## Overview
I use [Credit Card customers](https://www.kaggle.com/sakshigoyal7/credit-card-customers) dataset to build a classifier model to identify which customers are probably going to churn. This kind of classifier is significant to the business owner because if possible churners are identified, the business owner could make plans to prevent them from churning, thus reducing the loss of customers.

Among the models I tried, Random Forest Classifier, AdaBoost Classifier, and Support Vector Machines works well. Among them, Random Forest Classifier works best, with max_depth=50, max_features=15, and n_estimators=140.

## Results
- recall: 0.904
- precision: 0.83
- f1_score: 0.86
- balanced accuracy score: 0.93