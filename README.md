# ad-click-prediction-logistic-regression# Ad Click Prediction using Logistic Regression

## Project Overview

This project focuses on predicting whether a user will click on an online advertisement using Logistic Regression.

The project is based on a digital advertising business scenario for AdVantage Analytics, where understanding user behaviour and predicting ad clicks can help improve advertising targeting decisions.

## Business Problem

Digital advertising platforms need to understand which users are more likely to interact with advertisements.

The objective is to build a machine learning classification model that predicts whether a user will click on an advertisement based on demographic information, device type, ad characteristics and previous user behaviour.

## Project Objectives

- Analyze user behaviour and advertising performance.
- Perform Exploratory Data Analysis (EDA).
- Identify relationships between user characteristics and ad clicks.
- Handle missing values and prepare data for modelling.
- Apply statistical hypothesis testing.
- Build a Logistic Regression classification model.
- Evaluate model performance using classification metrics.
- Analyze prediction probabilities and decision thresholds.

## Dataset Information

The dataset contains 10,000 records and 13 columns.

**Target Variable:** `Clicked`

- 0 – Not Clicked
- 1 – Clicked

The input features include:
- Age
- Gender
- Geographic Location
- Device Type
- Ad Position
- Ad Category
- Day of Week
- Time of Day
- Time Spent on Site
- Previous Clicks

*Dataset access: Add the authorised dataset source or download instructions here.*

## Tools & Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Plotly
- SciPy
- Scikit-learn
- Statsmodels
- Jupyter Notebook
- Power BI (dashboard planned)

## Project Workflow

1. Business Understanding
2. Data Loading and Inspection
3. Data Cleaning
4. Exploratory Data Analysis
5. Missing Value Treatment
6. Statistical Hypothesis Testing
7. Correlation Analysis
8. Feature Engineering
9. Train-Test Split
10. Data Preprocessing
11. Logistic Regression Model Building
12. Model Evaluation
13. Probability Analysis
14. Decision Threshold Adjustment

## Model Performance

The current Logistic Regression model achieved the following results on the held-out test dataset:

| Metric | Score |
|---|---:|
| Accuracy | 87.40% |
| Precision (Class 1) | 100.00% |
| Recall (Class 1) | 82.30% |
| F1-Score (Class 1) | 90.29% |

A threshold adjustment from 0.50 to 0.30 was also explored to study the trade-off between precision and recall.

## Key Observations

- The dataset contains a higher proportion of clicked advertisements (71.18%).
- Device type shows a statistically significant association with ad-click behaviour.
- All mobile records in this dataset belong to the clicked class, which requires further investigation.
- Previous clicks did not show a statistically significant difference between the two target groups in the Mann-Whitney U test.

## Limitations

- The dataset contains an unusual perfect association between mobile device usage and ad clicks.
- Model performance should be validated on additional independent data.
- Feature engineering and multicollinearity analysis require further refinement.
- Model performance does not establish real-world advertising ROI.

## Future Improvements

- Compare Logistic Regression with other classification algorithms.
- Improve feature selection and feature engineering.
- Perform cross-validation and hyperparameter tuning.
- Evaluate ROC-AUC and PR-AUC
- Develop an interactive Power BI dashboard

## Author

**Ria Katkar**

Aspiring Data Analyst | Data Science Learner


