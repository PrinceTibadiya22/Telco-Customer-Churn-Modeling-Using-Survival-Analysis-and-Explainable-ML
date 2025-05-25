# Telco Customer Churn Survival Analysis and Explainable ML

This repository presents an end-to-end survival analysis and explainable machine learning approach to predicting and understanding customer churn for a telecommunications company. The project leverages the Telco Customer Churn dataset and combines classical statistical modeling with state-of-the-art interpretable machine learning to inform business retention strategies.

## Project Overview

The primary objective of this project is to identify the factors driving customer churn, estimate customer survival probabilities, and generate actionable insights for retention, using both statistical survival analysis and explainable ML methods.

The analysis follows these key stages:

- **Data Preprocessing:** Data cleaning, handling missing values, encoding categorical variables, and feature engineering.
- **Survival Analysis Setup:** Definition of duration and event variables for modeling time until churn.
- **Exploratory Data Analysis (EDA):** Visualization of churn and tenure distributions, Kaplan-Meier survival curves, and group-wise analysis by contract type and other key features.
- **Survival Modeling:** Application of the Cox Proportional Hazards model to quantify the impact of multiple customer attributes on churn risk.
- **Explainable ML:** Use of XGBoost and SHAP to predict churn and explain individual and global feature importance.
- **Customer-Level Outputs:** Generation of survival curves, churn risk tables, and interpretable explanations at the customer level.
- **Conclusions:** Clear recommendations for business actions based on analytical findings.

## Key Insights

- **Contract type is the dominant predictor of churn:** Two-year contracts dramatically reduce churn risk, while month-to-month contracts are the highest risk group.
- **Payment method matters:** Customers paying by mailed or electronic check exhibit higher churn, while credit card and automatic bank transfers are associated with greater stability.
- **Support features (Tech Support, Online Security) and partner status contribute to retention.**
- **Early tenure is the most vulnerable period for churn; most churn occurs within the first year.**
- **Explainable machine learning (SHAP) enables transparent, customer-level insight into churn risk drivers.**
