# E-Commerce Fraud Detection using Random Forest

## 📖 Overview

This project develops an end-to-end machine learning pipeline for fraud detection using a synthetic e-commerce transaction dataset. The workflow combines data preprocessing, feature engineering, class balancing, and supervised machine learning to identify fraudulent transactions while addressing severe class imbalance.

A dataset containing **23,634 synthetic e-commerce transaction records** was processed through data cleaning, temporal feature engineering, categorical encoding, feature scaling, and **SMOTE** oversampling before training a **Random Forest** classifier.

The project demonstrates how machine learning can be applied to improve fraud detection performance in highly imbalanced datasets while reducing the likelihood of undetected fraudulent transactions.

---

## 🎯 Business Problem

Fraudulent transactions account for only a small proportion of total e-commerce transactions but can result in significant financial losses. Traditional classification models often become biased toward the majority class, making fraudulent transactions difficult to identify accurately.

---

## 💡 Solution

This project develops a fraud detection pipeline by performing data preprocessing, temporal feature engineering, categorical encoding, feature scaling, and **SMOTE** oversampling to address severe class imbalance before training a **Random Forest** classifier. Model performance is evaluated using classification metrics with particular attention to fraud detection performance.

---

## 📂 Dataset

- **Dataset:** Fraudulent E-Commerce Transactions
- **Source:** Kaggle
- **Size:** 23,634 synthetic transaction records
- **Type:** Synthetic e-commerce transaction dataset

---

## ⚙️ Project Workflow

```text
Raw Transaction Data
        │
        ▼
Exploratory Data Analysis (EDA)
(Data Structure Analysis,
Missing Value Analysis,
Feature Distribution,
Correlation Analysis)
        │
        ▼
Data Preprocessing
(Data Cleaning,
Temporal Feature Engineering,
Categorical Encoding,
Feature Scaling)
        │
        ▼
SMOTE Oversampling
(Class Balancing)
        │
        ▼
Random Forest Classification
        │
        ▼
Model Evaluation
(Accuracy,
Precision,
Recall,
F1-Score,
Confusion Matrix)
        │
        ▼
Fraud Prediction
```

---

## 📊 Results

- Processed **23,634 synthetic e-commerce transaction records** for fraud detection.
- Applied **SMOTE** to address severe class imbalance before model training.
- Achieved **83.44% classification accuracy** on the test set.
- Achieved **61% fraud recall**, improving the model's ability to identify fraudulent transactions in an imbalanced dataset.

---

## 📁 Repository Structure

```text
ecommerce-fraud-detection-random-forest/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── fraud_detection.ipynb
│
└── data/
    └── fraud_dataset.csv
```
