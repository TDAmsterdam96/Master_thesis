Cryptocurrency Fraud Detection: Supervised Machine Learning for Illicit Ethereum Transactions
======================================================

> Master thesis submitted at the Faculty of Economics and Business (Sectie Finance) at Universiteit van Amsterdam (UvA)

[![License MIT](http://img.shields.io/badge/license-MIT-brightgreen.svg)](license.md)

> **Author**: [Thomas Dornigg](https://www.linkedin.com/in/thomas-dornigg/) <br>
> **Supervisor**: Prof. Torsten JOCHEM <br>
> **Academic year**: 2021/22

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

<p align="center">
  <img alt="Dark" src="https://github.com/ThomasD96/University_Repo/blob/master/University_of_Amsterdam/Master_thesis/Pictures/UVA-amsterdam-business-school.png" width="60%">
</p>

## Overview


Regarding the machine learning problem we are facing in this project, since we are trying to build and train a model to predict whether an Ethereum transaction is fraudulent or not, it is clearly a classification problem where we have two different classes to group the data:

- Supervised: The labels are included in the training data and the goal is to train a model to learn to predict the labels from the features

- Classification: The label is a binary variable, 0 (fraudulent transaction), 1 (fraudulent transaction)

In this project, the goals achieved are :
- Data Exploration routines are designed and implemented to do standard statistical analysis and visualization.
- Classification models such as Logistic Regression, Random Forest, XGBoost, Decision Tree, AdaBoost and Support Vector Machine are built to predict whether or not a transaction is fraudulent
- Evaluated Classification models by Accuracy, Precision, Recall, True Negative Rate, True Positive Rate, False Negative Rate, False Positive Rate and ROC – AUC chart

## Data Sources
The dataset **"Ethereum Fraud Detection Dataset"** for this project can be found on <a href="https://www.kaggle.com/vagifa/ethereum-frauddetection-dataset">Kaggle</a>. This dataset contains rows of known fraud and valid transactions made over Ethereum, a type of cryptocurrency, with a total of approx. 9,841 transactions and 49 features related to each of the transactions' history. Along with it, there are more specific information provided about every particular borrower. A full list of variables can be found below:
