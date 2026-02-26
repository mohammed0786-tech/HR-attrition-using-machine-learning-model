HR EMPLOYEE ATTRITION PREDICTION SYSTEM
=======================================

PROJECT OVERVIEW
----------------
This project focuses on predicting employee attrition using Machine Learning.
Employee attrition refers to employees leaving an organization due to resignation,
career change, dissatisfaction, or other factors.

The goal of this project is to help HR teams identify high-risk employees early
and take preventive actions to improve employee retention.

Problem Statement:
Organizations face productivity and financial loss when employees leave.
This system predicts whether an employee is likely to stay or leave based on
historical HR data.

------------------------------------------------------------

DATASET
-------
Dataset Used:
HR Employee Attrition Dataset (CSV format)

Target Variable:
Attrition
Yes -> Employee Left
No -> Employee Stayed

Selected Features:
- Age
- MonthlyIncome
- JobLevel
- TotalWorkingYears
- YearsAtCompany

------------------------------------------------------------

TECHNOLOGIES USED
-----------------
Programming Language:
- Python

Libraries:
- Pandas (Data Manipulation)
- NumPy (Numerical Operations)
- Matplotlib (Visualization)
- Seaborn (Statistical Graphs)
- Scikit-learn (Machine Learning Models)

Tools:
- Visual Studio Code
- Jupyter Notebook
- Power BI (Dashboard Visualization)

------------------------------------------------------------

DATA PREPROCESSING
------------------
Steps Performed:

1. Loaded dataset using Pandas.
2. Checked missing values.
3. Converted Attrition column using Binary Label Encoding:
   Yes -> 1
   No -> 0
4. Selected important numerical features.
5. Checked duplicates and cleaned data.

------------------------------------------------------------

MODEL BUILDING
--------------
Machine Learning Algorithms Used:

- Logistic Regression (Baseline Model)
- Random Forest Classifier (Improved Accuracy)

Train Test Split:
80% Training Data
20% Testing Data

Stratified Sampling used to maintain class balance.

------------------------------------------------------------

MODEL EVALUATION METRICS
------------------------
Performance evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC Score

Confusion Matrix used for classification analysis.

------------------------------------------------------------

MODEL INTERPRETABILITY
----------------------
SHAP (SHapley Additive Explanations) used to understand:

- Feature importance
- Model decision behavior.

Helps HR understand why employees are predicted as high risk.

------------------------------------------------------------

OUTPUT
------
Generated Columns:

- Predicted_Attrition (0 or 1)
- Predicted_Status
  Will Stay
  High Risk

Predictions exported as CSV file.

------------------------------------------------------------

POWER BI DASHBOARD
------------------
Three Dashboard Pages Created:

1. Executive Overview
   - Total Employees
   - High Risk Employees
   - Attrition Distribution
   - Department Analysis

2. Root Cause Analysis
   - Income Impact
   - Age Trends
   - Experience Factors

3. Prediction Insights
   - Risk Distribution by Department
   - Salary vs Tenure Insights
   - Key KPI Indicators

------------------------------------------------------------

BUSINESS IMPACT
---------------
Helps HR to:

- Identify employees likely to leave.
- Reduce hiring costs.
- Improve retention strategies.
- Make data-driven workforce decisions.

------------------------------------------------------------

FUTURE IMPROVEMENTS
-------------------
- Deploy as Web Application.
- Use Deep Learning Models.
- Real-time HRMS integration.

------------------------------------------------------------

AUTHOR
------
Mohammed Ashik

Role:
Data Analyst / Machine Learning Enthusiast

------------------------------------------------------------
