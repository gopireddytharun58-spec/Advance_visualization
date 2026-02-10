
### 📄 Customer Churn Analysis Report


#### 1. Introduction

Customer churn is a critical metric for subscription‑based businesses. This project analyzes churn patterns using a telecom dataset, aiming to identify key drivers of churn and provide actionable recommendations to improve retention.

#### 2. Dataset Overview

- File: customer_churn.csv
- Columns:
- CustomerID (unique identifier)
- Tenure (months with company)
- MonthlyCharges
- TotalCharges
- Contract (Month‑to‑month, One year, Two year)
- PaymentMethod (Credit Card, Bank Transfer, Electronic Check)
- PaperlessBilling (Yes/No)
- SeniorCitizen (binary flag)
- Churn (target variable: 0 = retained, 1 = churned)

#### 3. Workflow 

- Day 1: Data Loading & Exploration

- Loaded dataset with pandas.
- Checked structure, summary statistics, and missing values.
- No major missing values found.

- Day 2: Data Cleaning & Preparation

- Dropped unnecessary identifiers (CustomerID).
- Encoded categorical variables using one‑hot encoding.
- Created calculated columns (e.g., Average Monthly Spend, Lifetime Value).

#### Day 3: Customer Analysis

- Identified top customers by revenue.
- Calculated Customer Lifetime Value (CLV).
- Observed churn distribution across demographics.

#### Day 4: Sales Pattern Analysis

- Grouped by contract type → Month‑to‑month contracts had highest churn.
- Grouped by payment method → Electronic Check users churned more frequently.
- Analyzed tenure vs churn → longer tenure correlated with lower churn.

#### Day 5: Advanced Analysis

- Created pivot tables for churn by contract and payment method.
- Calculated retention rate (~80–85%).
- Identified cross‑selling opportunities (e.g., senior citizens with electronic check payments).

#### Day 6: Dashboard Creation

- Built 5 key visualizations:
- Churn distribution (pie chart).
- Contract type vs churn (bar chart).
- Payment method vs churn (stacked bar chart).
- Tenure vs churn (line chart).
- Monthly vs Total Charges (scatter plot).

#### Day 7: Report & Insights

- Month‑to‑month contracts are most vulnerable to churn.
- Electronic check payment method is strongly associated with churn.
- Senior citizens show slightly higher churn risk.
- Customers with longer tenure are more loyal.

#### 4. Business Recommendations

- Incentivize long‑term contracts (discounts, loyalty rewards).
- Encourage secure payment methods (credit card, bank transfer) over electronic checks.
- Target retention programs for senior citizens and high‑risk groups.
- Onboard new customers effectively to reduce early churn.

#### 5. Conclusion

This project provides a structured 7‑day analysis of customer churn. By combining exploratory data analysis, advanced analytics, and visualization, we identified key churn drivers and proposed actionable strategies to improve retention.
