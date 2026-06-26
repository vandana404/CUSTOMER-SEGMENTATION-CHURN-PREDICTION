# Customer Churn Prediction and Customer Segmentation

## Project Overview

This project aims to predict customer churn and segment customers into meaningful groups using Machine Learning techniques. The objective is to help businesses identify customers who are likely to leave and develop targeted retention strategies.

The project combines:

* Data Cleaning and Exploratory Data Analysis
* Feature Selection and Train Test Split
* RandomForest 
* Recall optimization by using Hyperparameter Tunning
* Cross Validation of the data set
* calulate the Roc-auc score
* Customer segmentation using the K-means
* Data visualization using seaborn and matplotlib
  

---

## Business Problem-Churn Segmentaion of customers

Customer churn Segmentation which is a major challenge for subscription-based businesses like companies(IBM,TCS ,Big MNC etc). Losing existing customers increases acquisition costs and reduces revenue also we need good resources and their requirements to retain the customers.

This project helps answer:

* Which customers are likely to churn?
* What factors influence churn?
* How can customers be segmented based on behavior and risk?
* How many customer leave the company in a year or how much sustain more than a year
* Key factors behind the loosing the customers

---

## Dataset

The dataset contains customer  information, service usage details(Internet services,tech support,Total Charges), contract information, billing information,Tenure Month, and churn status(churn value,churn score).

### Key Features used in this project-

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
* Machine Learning
* Matplotlib
* K-means
* RandomForest
* PCA analysis
* Roc-auc Score Analysis
* Seaborn
* Scikit-Learn

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

Performed:

* Distribution Analysis
* Encoding
* Data Cleaning
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
* Real-time Churn Prediction API

