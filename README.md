# Customer Retention & Churn Analysis

**Future Interns — Data Science & Analytics Internship | Task 2**

## Project Overview

Customer retention is an important factor in the sustainability and growth of subscription-based businesses. This project analyses customer churn patterns using the Telco Customer Churn dataset and presents the findings through an interactive Microsoft Power BI dashboard.

The objective is to identify customer segments associated with higher churn, understand service and payment-related patterns, and develop actionable business recommendations.

## Objectives

- Analyse overall customer churn and retention.
- Identify churn patterns across customer demographics.
- Examine the relationship between customer tenure, monthly charges, and churn.
- Investigate payment methods and subscribed services associated with churn.
- Present findings through interactive Power BI dashboards.
- Develop practical customer-retention recommendations.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Data preparation, modelling, visualisation, and reporting |
| Power Query | Data import and preparation |
| DAX | Measures and calculations |
| CSV | Dataset format |

## Dataset

**Name:** Telco Customer Churn

**Source:** [Kaggle — Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

| Dataset Attribute | Value |
|---|---:|
| Total Customers | 7,043 |
| Total Columns | 21 |
| Churned Customers | 1,869 |
| Retained Customers | 5,174 |

The dataset contains customer demographics, subscribed services, account information, billing details, and churn status.

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Customers | 7,043 |
| Churned Customers | 1,869 |
| Retained Customers | 5,174 |
| Churn Rate | 26.54% |
| Retention Rate | 73.46% |

## Dashboard Structure

The Power BI report consists of four analytical pages.

### 1. Churn Overview
- Total customers
- Churned customers
- Retained customers
- Overall churn rate
- Customer churn versus retention
- Churn by contract type

### 2. Customer Segmentation
- Churn by gender
- Churn by senior-citizen status
- Churn by internet-service category

### 3. Retention & Tenure Analysis
- Customer churn by tenure
- Churn rate by customer tenure
- Customer churn by monthly charges

### 4. Churn Drivers & Recommendations
- Churn rate by payment method
- Churn rate by technical-support availability
- Churn rate by online-security availability
- Business insights and recommendations

## Key Findings

The analysis identified the following patterns:

1. Electronic-check users showed the highest churn rate among the displayed payment methods.
2. Customers without technical support showed the highest churn rate among the technical-support categories.
3. Customers without online security showed the highest churn rate among the online-security categories.
4. The overall customer churn rate was 26.54%, indicating an opportunity to strengthen retention strategies.

These findings represent associations in the dataset and do not establish direct causation.

## Business Recommendations

- Investigate payment-related friction among electronic-check users.
- Improve awareness and accessibility of technical-support services.
- Promote the benefits of online-security services.
- Develop targeted retention strategies for higher-risk customer segments.
- Monitor churn and retention performance regularly.

## Project Structure

```text
FUTURE_DS_02_CUSTOMER_CHURN/
│
├── DATASET/
│   └── Telco-Customer-Churn.csv
│
├── POWERBI/
│   ├── FUTURE_DS_02_Customer_Churn.pbix
│   └── FUTURE_DS_02_Customer_Churn.pdf
│
├── Screenshots/
│   ├── 01_Churn_Overview.png
│   ├── 02_Customer_Segmentation.png
│   ├── 03_Retention_Tenure_Analysis.png
│   └── 04_Churn_Drivers.png
│
├── DOCUMENTATION/
│   ├── Business_Insights.pdf
│   └── Data_Dictionary.pdf
│
└── README.md
```

## Project Deliverables

- Power BI dashboard (`.pbix`)
- Exported dashboard report (`.pdf`)
- Four dashboard screenshots
- Business Insights report (`.pdf`)
- Dataset Data Dictionary (`.pdf`)

## Conclusion

This project demonstrates how business intelligence and data visualisation can be used to investigate customer churn, identify higher-risk customer segments, and support data-informed retention strategies.

The resulting dashboard provides a structured view of customer behaviour and a foundation for further customer-retention analysis.

---

**Project:** Future Interns — Task 2  
**Domain:** Data Science & Analytics  
**Primary Tool:** Microsoft Power BI Desktop