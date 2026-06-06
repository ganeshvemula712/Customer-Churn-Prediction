
# Customer Churn Prediction Using Machine Learning

## Project Overview

Customer churn is one of the most important business challenges faced by subscription-based companies. This project predicts whether a customer is likely to leave the service using Machine Learning techniques.

The objective is to identify customers at risk of churning and help businesses take proactive retention measures.

---

## Problem Statement

Customer acquisition is expensive. Retaining existing customers is more cost-effective than acquiring new ones.

This project aims to:

* Analyze customer behavior
* Identify churn patterns
* Build predictive models
* Generate actionable business insights

---

## Dataset

The dataset contains customer information including:

* Gender
* Senior Citizen Status
* Partner Status
* Dependents
* Tenure
* Monthly Charges
* Total Charges
* Contract Type
* Payment Method
* Internet Services
* Churn Status

Target Variable:

**Churn**

* 0 = Customer Retained
* 1 = Customer Left

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Train-Test Split
7. Feature Scaling
8. Model Building
9. Model Evaluation
10. Business Insights

---

## Machine Learning Models Used

### Logistic Regression

* Simple and interpretable model
* Performed best on this dataset

### Random Forest Classifier

* Ensemble learning algorithm
* Used for comparison

---

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 78.75%   |
| Random Forest       | 78.46%   |

### Best Model

**Logistic Regression**

---

## Key Business Insights

* Customers with higher monthly charges are more likely to churn.
* Customers with shorter tenure have higher churn risk.
* Month-to-month contracts increase churn probability.
* Additional services such as Tech Support and Online Security improve customer retention.
* Predictive analytics can help businesses reduce customer loss and improve revenue.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Future Improvements

* Hyperparameter Tuning
* XGBoost Implementation
* Deployment using Streamlit
* Real-Time Churn Prediction System

---

## Author

Ganesh Vemula

B.Tech (Data Science)

Aspiring Data Analyst | Machine Learning Enthusiast

Customer Churn Prediction using Machine Learning
Project Overview

This project predicts customer churn using Machine Learning techniques. Customer churn refers to customers who discontinue a company's service. Predicting churn helps businesses identify at-risk customers and improve retention strategies.

The project uses the Telco Customer Churn Dataset and compares multiple machine learning algorithms to determine the best-performing model.

Business Problem

Customer retention is critical for subscription-based businesses. Losing customers leads to revenue loss and increased acquisition costs.

This project aims to:

Identify customers likely to churn
Understand factors influencing churn
Build a predictive machine learning model
Generate actionable business insights
Dataset Information

Dataset: Telco Customer Churn Dataset

Features include:

Gender
Senior Citizen
Partner
Dependents
Tenure
Phone Service
Internet Service
Contract Type
Payment Method
Monthly Charges
Total Charges

Target Variable:

Churn
0 = Customer Stays
1 = Customer Leaves
Project Workflow
1. Data Collection

Loaded Telco Customer Churn Dataset.

2. Data Cleaning
Removed missing values
Fixed data types
Checked duplicates
3. Exploratory Data Analysis (EDA)

Performed:

Churn distribution analysis
Contract analysis
Tenure analysis
Monthly charges analysis
4. Feature Engineering

Converted categorical variables into numerical variables using One-Hot Encoding.

5. Data Splitting
Train Data = 80%
Test Data = 20%
6. Feature Scaling

Applied StandardScaler for normalization.

7. Model Building

Models trained:

Logistic Regression
Random Forest Classifier
8. Model Evaluation

Metrics used:

Accuracy Score
Classification Report
Confusion Matrix
Model Performance
Model	Accuracy
Logistic Regression	78.75%
Random Forest	78.46%
Best Model

✅ Logistic Regression

Final Accuracy:

78.75%
Key Business Insights
Insight 1

Customers with higher monthly charges are more likely to churn.

Insight 2

Customers with shorter tenure show higher churn rates.

Insight 3

Month-to-month contracts contribute significantly to churn.

Insight 4

Customers lacking additional services are more likely to leave.

Insight 5

Early churn prediction can help businesses improve retention strategies.

Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Joblib
Environment
Jupyter Notebook
Git
GitHub
Project Structure
Customer-Churn-Prediction
│
├── Data
│   └── Telco_Customer_Churn_Dataset.csv
│
├── Notebooks
│   └── Customer_Churn_Prediction.ipynb
│
├── Models
│   └── logistic_regression_model.pkl
│
├── Images
│
├── requirements.txt
├── .gitignore
└── README.md
Model Saving
import joblib

joblib.dump(model,
            "Models/logistic_regression_model.pkl")
Future Improvements
Hyperparameter Tuning
XGBoost Implementation
Deployment using Streamlit
Real-time Churn Prediction
Cloud Deployment
Author
Ganesh Vemula

B.Tech CSE (Data Science)

Interested in:

Data Analytics
Machine Learning
Artificial Intelligence

GitHub:
https://github.com/ganeshvemula712

LinkedIn:
https://www.linkedin.com/in/ganesh-vemula-951833303?utm_source=share_via&utm_content=profile&utm_medium=member_android

