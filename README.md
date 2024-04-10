# Project Description

## Introduction to Credit Card Fraud Detection Project
Like any other technology that has been introduced in the world, the internet also comes with pros and cons. All of us enjoy the pros as the internet has changed our lifestyle by enhancing our communication. But, at the same time, we are witnessing digital frauds, which include fraudulent transactions through stolen credit cards. Credit card companies must identify fraudulent credit card transactions so that customers are not charged for items that they did not purchase. And this project is all about detecting such fraudulent transactions with the help of customers' attributes and transactions information.

## Credit Card Fraud Detection Dataset
The dataset used contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced; the positive class (frauds) account for 0.172% of all transactions. The dataset has been collected and analyzed during a research collaboration of Worldline and the Machine Learning Group of ULB on big data mining and fraud detection.

As the dataset was created using the PCA method, preprocessing of data has little scope. The imbalance between classes is compensated using oversampling and undersampling. The logistic regression, random forest, support vector machine, k-means are used within a cross-validation framework. Lastly, Recall and Accuracy are chosen as metrics while deducing the best classifier. A buffer section on outlier detection is added at the end.
