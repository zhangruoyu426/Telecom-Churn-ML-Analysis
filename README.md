# From Churn Prediction to Retention Strategy: A Machine Learning-Based Analysis for Telecommunication Service Provider

---

## Overview

Customer churn represents a significant financial risk for telecommunications service providers, as recurring revenue erosion from departing customers can reduce long-term profitability and increase customer acquisition costs.

This project develops an end-to-end analytical framework that moves from **customer churn prediction to actionable retention strategy and financial evaluation**. Using the publicly available [IBM Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data), the analysis integrates:

1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Customer segmentation using K-means clustering
4. Churn prediction using multiple machine learning classifiers
5. Model interpretation using SHAP
6. Retention campaign design
7. Monte Carlo simulation of campaign profitability
8. Sensitivity analysis of financial outcomes

The objective is not only to predict **who is likely to churn**, but also to identify **which customer segments are most at risk and whether targeted retention intervention is financially worthwhile**.

---

## Key Results

| Analysis | Key Finding |
|---|---|
| Overall churn rate | **26.54%** |
| Customer segmentation | **2 distinct behavioral clusters** |
| Cluster churn difference | **ANOVA p = 0.0487** |
| Best churn model | **Lasso Logistic Regression** |
| Holdout Set recall | **0.7889** |
| Simulation trials | **500 Monte Carlo trials** |
| Probability of positive campaign impact | **100%** |
| Expected net campaign impact | **USD 53,099** |
| Sensitivity analysis range | **USD 22,579–84,613** |

### Major Findings

- **Tenure, internet service tier, and contract length** are among the strongest factors associated with customer churn.
- K-means clustering identifies two statistically distinct customer groups, primarily separated by **tenure and monthly expenditure**.
- The clusters exhibit significantly different churn rates, suggesting that customer segmentation can provide additional context for retention strategy.
- Among Lasso Logistic Regression, Random Forest, and Gradient Boosting, **Lasso Logistic Regression achieved the highest cross-validated recall of 0.803**.
- A Monte Carlo simulation of a targeted retention campaign produces a **100% probability of positive net financial impact** under the modeled assumptions.
- Sensitivity analysis indicates that the campaign remains profitable across a broad range of customer acceptance rates.

See the full report [here](https://zhangruoyu426.github.io/Telecom-Churn-ML-Analysis/Report.html)
