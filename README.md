# Customer Churn Analysis
### Telco Customer Dataset | Python | Pandas | Matplotlib | Seaborn

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualisation-orange)

---

## Overview

This project explores customer churn behaviour across a telco dataset of 7,043 customers, identifying key churn drivers and high-risk segments to inform data-driven retention strategy.

The analysis covers data cleaning, exploratory data analysis (EDA) across six key variables, and a correlation heatmap to quantify relationships between customer characteristics and churn.

---

## The Question This Analysis Asks

> *"Which customers are most likely to churn, and what drives them to leave?"*

---

## Key Findings

| Finding | Detail |
|---|---|
| Overall churn rate | 26.5% (1,869 of 7,043 customers) |
| Highest risk contract type | Month-to-month at 42.7% churn |
| Highest risk tenure window | First 10 months of customer relationship |
| Average monthly charge — churned | USD 74.44 vs USD 61.27 retained |
| Highest risk internet service | Fiber optic at 41.8% churn |
| Highest risk payment method | Electronic check at 45.3% churn |

---

## Notebook Structure

The analysis is structured as a single Jupyter Notebook with the following sections:

**1. Data Loading & Inspection**
- Shape, column types, null value check, summary statistics

**2. Data Cleaning**
- Identified `TotalCharges` stored as string due to blank spaces
- Replaced blanks with NaN, converted to float64
- Filled 11 missing values with column median

**3. Exploratory Data Analysis**
- Churn distribution
- Churn by contract type
- Churn by tenure
- Churn by monthly charges (average + boxplot)
- Churn by internet service type
- Churn by payment method
- Churn by senior citizen status

**4. Correlation Analysis**
- Heatmap of numeric variables vs churn
- Tenure shows strongest negative correlation (-0.35)
- Monthly charges shows moderate positive correlation (0.19)

**5. Summary & Recommendations**
- Key findings consolidated
- Five data-driven retention recommendations

---

## Recommendations

1. **Prioritise contract conversion** — Incentivise month-to-month customers to upgrade to annual or two-year contracts through loyalty discounts or value-added benefits.
2. **Early tenure intervention** — Implement a structured onboarding and check-in programme for customers in their first 10 months to reduce early churn risk.
3. **Review Fiber Optic pricing and value proposition** — With a 41.8% churn rate, fiber optic customers are not perceiving sufficient value. A pricing or service quality review is warranted.
4. **Target electronic check users** — This segment churns at 45.3%. Incentivising a switch to automatic payment methods could improve both retention and payment reliability.
5. **Senior citizen retention programme** — Senior citizens churn at nearly double the rate of non-senior customers and would benefit from tailored pricing or support offerings.

---

## Dataset

**IBM Telco Customer Churn Dataset**
- Source: [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- 7,043 rows, 21 columns
- Mix of customer demographics, service subscriptions, account information, and churn status

---

## Tools Used

| Tool | Purpose |
|---|---|
| Python | Core analysis language |
| Pandas | Data manipulation and cleaning |
| Matplotlib | Data visualisation |
| Seaborn | Correlation heatmap |
| Jupyter Notebook | Analysis environment |

---

## Files in This Repository

```
├── Customer_churn_analysis.ipynb    # Full analysis notebook
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset
└── README.md
```

---

## Author

**Jordan Nel** — Customer Relations & Insights Specialist | Python | SQL | Power BI  
[LinkedIn](https://www.linkedin.com/in/jordan-nel) · [GitHub](https://github.com/hjnel3-droid)
