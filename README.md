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
| **Top spending category** | Smartwatch, Smartphone and Laptop |
| **Demographic pattern** | Miami has the highest total sale while New York placed last |
| **Payment behavior** | 40% of transaction is paid with PayPal, collecting $35.170,00 |

---

## Business Questions

1. Which product categories drive the most consumer spending?
2. Are there identifiable spending peaks by time period?
3. How do spending behaviors differ across demographics?
4. What patterns exist in payment method usage?

---

## Dashboard

<img width="1015" height="882" alt="image" src="https://github.com/user-attachments/assets/163c9bf1-000c-4e35-99db-e3e1fd100fc2" />

**Dashboard features:**
- KPI Cards: Total sales, total success order, average order value, top 3 best selling products
- Payment method percentange (pie chart)
- Total sales each location (bar chart)
- Interactive slicers: Location

---

## Process

**1. Data Understanding**
- Imported raw CSV, applied text-to-columns, converted to Excel Table
- Checked data types, missing values, and outliers in transaction amounts

**2. Data Preparation (Power Query)**
- Standardized column names and data types
- Created calculated columns: , `Month` and `Day`
- Removed duplicate and incomplete transaction records

**3. Analysis (Pivot Table)**
- Analyzed sales patterns by month and day of the week
- Evaluated revenue distribution by state and city
- Ranked products by volume, revenue, and sales percentage.
- Identified top customers by expenditure and order frequency.
- Compared revenue and usage across payment methods.
- Calculated total sales, order volume, and Average Order Value (AOV).

**4. Visualization**
- Single-page interactive dashboard
- Dynamic slicer

---

## Repo Structure

```
excel-retail-spending-analysis/
├── data/
│   └── raw_amazon_sales_data 2025.xlxs     # Original dataset
│   └── fix_amazon_transaction_all.xlxs     # Clean dataset
├── reports/
│   └── Amazon 2025 Sales Analysis (Dashboard + Dataset).xlsx  # Excel workbook + dashboard
│   └── snapshot_consumer_trends.pdf # Dashboard snapshot in PDF
└── README.md
```

---

## Tools Used

`Microsoft Excel` `Power Query` `Pivot Table` `Pivot Chart` `Slicers`

---

*Part of my [data portfolio](https://github.com/ramayogas/data-portofolio) — Rama Yogaswara*
