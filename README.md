📊 Bank-Data-Analysis
📝 Project Overview

This project focuses on analyzing bank customer data to extract insights on loan approvals, default risk, and customer segmentation. The goal is to support better decision-making in lending services and risk management.

🎯 Objectives

Perform Exploratory Data Analysis (EDA) on customer and loan datasets.

Identify patterns in customer demographics, income, loan amounts, and repayment behavior.

Build predictive models to estimate the likelihood of loan approval or default.

Create visualizations and dashboards for decision support.

🗂️ Dataset

Contains customer information such as:

Customer ID

Age, Gender, Marital Status

Income, Credit Score, Employment Status

Loan Amount, Loan Type, Loan Status

Rows: ~50K – 200K (depending on source).

File format: .csv

🔧 Tools & Technologies

Python → Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

SQL → Data extraction, cleaning, joins

Tableau / Power BI → Dashboards and insights

Excel → Quick summaries, pivot tables

📈 Methodology

Data Cleaning & Preprocessing

Handle missing values, outliers

Encode categorical variables (OneHot, Label Encoding)

Normalize/scale numeric features

Exploratory Data Analysis (EDA)

Customer demographics distribution

Income vs Loan Amount trends

Default rate by age, employment type, credit score

Feature Engineering

Debt-to-Income Ratio (DTI)

Loan-to-Value Ratio (LTV)

Derived risk categories

Model Building

Logistic Regression → Loan approval prediction

Random Forest / XGBoost → Default classification

KMeans → Customer segmentation

Evaluation Metrics

Accuracy, Precision, Recall, F1-score

ROC-AUC Curve

Confusion Matrix

📊 Key Insights

Customers with low credit score + high DTI → higher default probability.

Married + salaried individuals had higher approval rate.

Segmentation revealed 3 main customer clusters:

Low-income, high-risk borrowers

Middle-income, stable repayment history

High-income, low-risk premium borrowers

📌 Outcomes

Built a Loan Approval Prediction Model with ROC-AUC ~0.78.

Risk dashboard created in Tableau for monitoring.

Recommendations: tighten approval for high-DTI group, increase monitoring for cluster-1 customers.

🚀 Future Work

Deploy model via Streamlit / Flask as an interactive app.

Integrate real-time data pipelines using SQL + Airflow.

Add Explainable AI (SHAP/LIME) for feature importance transparency.
