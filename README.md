# Credit Card Fraud Detection System

## A Machine Learning System for Real-Time Transaction Analysis

This repository contains an intelligent machine learning system designed and implemented to detect fraudulent credit card transactions in real time. The primary objective is to provide a robust, scalable, and intelligent solution to help financial institutions prevent losses and protect users by immediately analyzing each transaction as it occurs.

The system integrates multiple models and uses advanced feature engineering to enhance detection performance and improve model reliability.

## Features

* **Real-Time Fraud Detection:** Enables immediate analysis and classification of transactions to quickly identify and flag potential fraud.
* **Ensemble Model Integration:** Combines the predictive strengths of Random Forest and XGBoost classifiers to boost detection accuracy and reduce the number of false positives.
* **Advanced Feature Engineering:** Implements sophisticated feature creation, including geospatial analysis (e.g., calculating the distance between the cardholder's location and the merchant's location) to identify abnormal behavior.
* **Interactive Web Interface:** A user-friendly web application to manually enter transaction details (Merchant, Category, Amount, Location, etc.) and receive an instant prediction on whether the transaction is "Legitimate" or "Fraudulent".

## Technologies & Models Used

* **Machine Learning Models:** Random Forest, XGBoost
* **Core Libraries (Inferred):** Scikit-learn, Pandas, NumPy, XGBoost
* **Key Techniques:** Ensemble Learning, Real-Time Prediction, Geospatial Feature Engineering
* 
![Credit Card Fraud Detection Output](https://github.com/devray11/Credit-Card-Fraud-Detection/blob/715378ed953798059522895bd486246a13f9088d/Output-Image.png)
