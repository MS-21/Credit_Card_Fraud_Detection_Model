# Credit_Card_Fraud_Detection_Model
ML-Based Fraud Detection Classifier

## Overview
This project focuses on building an effective machine learning classification model to detect fraudulent credit card transactions. Fraud detection is critical in the financial industry, and this project demonstrates how to handle class imbalance, engineer features, and evaluate models for real-world deployment.

## Objectives
- Develop a robust fraud detection model.
- Handle extreme class imbalance in the dataset.
- Engineer meaningful features (e.g., transaction frequency, location mismatch).
- Compare multiple ML algorithms based on key performance metrics.
- Achieve high precision and recall while minimizing false positives.

 ## Algorithms Used
✅ Logistic Regression

✅ Random Forest
✅ XGBoost
✅ LightGBM
#### Each model was evaluated on:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC

## Dataset
- Source: Kaggle 
- Size: 284,807 transactions
- Fraudulent Cases: 492 (0.17%)
#### Features:
- Transaction Amount, Time
- PCA-transformed features (V1–V28)
- Class (0: Non-fraud, 1: Fraud)

## Feature Engineering
- Transaction Frequency per Card
- Amount per Merchant Category
- Time-based Features
- Location Mismatch (simulated in extended versions)
- Scaling using StandardScaler

## Handling Class Imbalance
- Applied SMOTE (Synthetic Minority Oversampling Technique)
- Ensured balance between minority and majority classes to prevent model bias

## Best Model
- Random Forest outperformed all models in terms of F1 Score and ROC AUC.
- It achieved nearly perfect fraud detection capability with minimal false positives.

## Future Improvements
- Real-time fraud detection system
- Deep learning model (LSTM/CNN for sequence modeling)
- Integration with web API for production
- Geo-based location tracking and mismatch detection


