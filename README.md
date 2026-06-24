# Customer Churn Prediction and Customer Segmentation

## Project Overview

This project aims to predict customer churn and segment customers into meaningful groups using Machine Learning techniques. The objective is to help businesses identify customers who are likely to leave and develop targeted retention strategies.

The project combines:

* Churn Prediction using Random Forest Classifier
* Customer Segmentation using K-Means Clustering
* Feature Importance Analysis
* Model Evaluation and Hyperparameter Tuning

---

## Business Problem

Customer churn is a major challenge for subscription-based businesses. Losing existing customers increases acquisition costs and reduces revenue.

This project helps answer:

* Which customers are likely to churn?
* What factors influence churn?
* How can customers be segmented based on behavior and risk?

---

## Dataset

The dataset contains customer demographic information, service usage details, contract information, billing information, and churn status.

### Key Features

* Tenure Months
* Monthly Charges
* Total Charges
* Contract Type
* Internet Service
* Payment Method
* Tech Support
* Churn Value

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

Performed:

* Distribution Analysis
* Boxplots
* Correlation Analysis
* Churn Pattern Analysis
* Contract-wise Churn Analysis

### 2. Data Preprocessing

* Missing value treatment
* Feature selection
* One-Hot Encoding
* Removal of irrelevant columns

### 3. Churn Prediction

Implemented Random Forest Classifier to predict customer churn.

### Model Improvements

#### Baseline Model

* Random Forest Classifier

#### Class Imbalance Handling

* class_weight='balanced'

#### Hyperparameter Tuning

* Number of Trees: 100–500
* Maximum Depth: 5–20

#### Cross Validation

* 5-Fold Cross Validation

---

## Feature Importance Analysis

Analyzed the most influential features affecting customer churn.

Important features include:

* Contract Type
* Monthly Charges
* Tenure Months
* Total Charges

---

## Model Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

---

## Customer Segmentation

After churn prediction, customers were segmented using K-Means Clustering.

### Features Used

* Tenure Months
* Monthly Charges
* Total Charges
* Churn Probability

### Cluster Segments

| Cluster | Segment Name            |
| ------- | ----------------------- |
| 0       | Budget Loyal Customers  |
| 1       | High-Risk Customers     |
| 2       | Loyal Premium Customers |

---

## Business Insights

### High-Risk Customers

* High probability of churn
* Require retention campaigns

### Budget Loyal Customers

* Long-term customers
* Low spending but stable

### Loyal Premium Customers

* High-value customers
* Suitable for upselling and premium services

---

## Future Improvements

* XGBoost Implementation
* SHAP Explainability
* Streamlit Dashboard
* Real-time Churn Prediction API
* Deployment on AWS/GCP

---

## Project Structure

├── data/
├── notebooks/
├── customer_churn_prediction.py
├── requirements.txt
├── README.md
└── outputs/

---
