# delinquency-risk-prediction
Exploratory Data Analysis and risk indicator identification for customer delinquency prediction using financial and behavioral data.
# Delinquency Risk Analysis

## Project Overview
This project focuses on Exploratory Data Analysis (EDA) of a customer-level financial dataset
to identify key risk indicators associated with account delinquency.

The objective is to assess data quality, understand behavioral and financial drivers of delinquency,
and evaluate the dataset’s readiness for predictive modeling in a financial services context.

## Dataset Description
The dataset contains customer demographic, financial, and behavioral attributes including:
- Age, Income, Credit Score
- Credit Utilization and Debt-to-Income Ratio
- Historical payment behavior across recent months
- Target variable indicating account delinquency

## Key Insights
- Recent late and missed payments are the strongest indicators of delinquency risk
- High credit utilization consistently correlates with higher delinquency probability
- High debt-to-income ratios indicate reduced repayment capacity
- Data quality issues such as missing income values and inconsistent categorical labels were identified and addressed

## Repository Structure
- `data/` – Raw and processed datasets
- `notebooks/` – Jupyter notebooks containing EDA and analysis
- `reports/` – PDF reports summarizing findings
- `docs/` – Dataset documentation and reference material

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Exploratory Data Analysis (EDA)
- Data Cleaning & Validation
- Risk Indicator Analysis

## Next Steps
- Feature engineering from payment history variables
- Supervised model development (Logistic Regression, Tree-based models)
- Model explainability using SHAP or feature importance

## Data Confidentiality
Due to data confidentiality and company policy, the original dataset used for this analysis
is not included in this repository.

The project focuses on demonstrating the analytical approach, risk identification logic,
and EDA methodology rather than data disclosure.

