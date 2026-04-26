# Retail Consumer Spending Analysis
**Tool:** Microsoft Excel (Power Query · Pivot Table · Dashboard)  
**Domain:** Retail / Consumer Behavior  
**Dataset:** [Consumer Trends Dataset — PayPal Miami (Kaggle)](https://www.kaggle.com/datasets/rabieelkharoua/the-miami-paypal-consumer-trends-dataset)

---

## Overview

Understanding where, when, and how consumers spend their money is fundamental to retail strategy. This project explores spending patterns and consumer behavior using transaction-level data from Miami — identifying trends across product categories, demographics, and payment behavior.

The goal: **surface actionable insights about consumer spending habits** through an interactive Excel dashboard.

---

## Key Findings

| Finding | Insight |
|---|---|
| **Top spending category** | *(update with actual finding from your data)* |
| **Peak spending period** | *(update with actual finding)* |
| **Demographic pattern** | *(update with actual finding)* |
| **Payment behavior** | *(update with actual finding)* |

> 📝 *Update this table with your actual findings after analysis*

---

## Business Questions

1. Which product categories drive the most consumer spending?
2. Are there identifiable spending peaks by time period?
3. How do spending behaviors differ across demographics?
4. What patterns exist in payment method usage?

---

## Dashboard

> 📸 *Screenshot dashboard menyusul — file Excel tersedia di folder `/reports`*

**Dashboard features:**
- KPI Cards: Total transactions, avg spend per customer, top category, peak period
- Spending by category (bar/column chart)
- Trend over time (line chart)
- Interactive slicers: Category, Gender, Age Group, Payment Method

---

## Process

**1. Data Understanding**
- Imported raw CSV, applied text-to-columns, converted to Excel Table
- Checked data types, missing values, and outliers in transaction amounts

**2. Data Preparation (Power Query)**
- Standardized column names and data types
- Created calculated columns: `Age Group`, `Spending Tier`, `Month`
- Removed duplicate and incomplete transaction records

**3. Analysis (Pivot Table)**
- Calculated total and average spend by category, demographic, and time period
- Identified top and bottom performing categories
- Compared spending patterns across demographic segments

**4. Visualization**
- Single-page interactive dashboard
- Slicers for dynamic filtering across all charts and KPIs

---

## Repo Structure

```
excel-retail-spending-analysis/
├── data/
│   └── consumer_trends_raw.csv     # Original dataset
├── reports/
│   └── retail_spending_analysis.xlsx  # Excel workbook + dashboard
└── README.md
```

---

## Tools Used

`Microsoft Excel` `Power Query` `Pivot Table` `Pivot Chart` `Slicers`

---

*Part of my [data portfolio](https://github.com/ramayogas/data-portofolio) — Rama Yogaswara*
