# SQL Data Analysis Project

> SQL-based Exploratory Data Analysis and Advanced Analytics to extract actionable business intelligence from a data warehouse.

---

## Overview

This project covers the full data analysis lifecycle — from initial data exploration to complex analytical reporting — using **SQL Server** and **T-SQL**. It delivers critical insights into customer behaviour and product performance through structured EDA and advanced SQL techniques.

---

## Repository Structure

```
sql-data-analysis-project/
│
├── Scripts/
│   ├── Change_Over_Time_Analysis.sql
│   ├── Cumulative_Analysis.sql
│   ├── Data_Segmentation.sql
│   ├── Magnitude_Analysis.sql
│   ├── Part_To_Whole_Analysis.sql
│   ├── Performance_Analysis.sql
│   ├── Ranking_Analysis.sql
│   ├── Report_Cust.sql
│   └── Report_Products.sql
├── DataWarehouseAnalytics.bak
└── Detailed_Insights
```

---

## Analytics Phases

### 1. Exploratory Data Analysis (EDA)
- **Database Profiling** — Investigating data distribution, identifying key dimensions and measures, and checking for data quality issues
- **Insight Discovery** — Uncovering business trends such as top-performing products and customer segments by combining descriptive dimensions with quantitative metrics

### 2. Advanced Data Analytics
- **Window Functions** — `RANK()`, `DENSE_RANK()`, `LEAD()`, `LAG()`, `SUM() OVER()` for time-series, month-over-month, and year-over-year comparisons
- **Complex Reporting** — Consolidated views addressing critical business questions for stakeholder reporting
- **CTEs & Subqueries** — Streamlining complex logic and enhancing query readability

---

## Key Business Insights

### Customer Insights

| Metric | Finding |
|--------|---------|
| Revenue Distribution | New (38%), VIP (37%), Regular (25%) — strong acquisition, weak long-term loyalty |
| Retention | 63% one-time buyers; 92% with lifespan under 6 months |
| Purchase Behaviour | High AOV of $911 but low Average Monthly Spend of $452 — infrequent high-value purchases |
| Top Demographic | Customers aged 50+ drive 66% of total revenue |
| Revenue Concentration | Top 20% of customers contribute only 34% of total revenue |

### Product Insights

| Metric | Finding |
|--------|---------|
| Category Dependency | 'Bikes' generates 96% of total revenue |
| Subcategory Risk | 'Road Bikes' alone contributes 50% of total revenue |
| Product Performance | A small set of products accounts for 94% of total revenue |
| Order Volume vs Revenue | 'Accessories' make up 60% of total orders but contribute relatively low revenue |

### Overall Conclusion

The business demonstrates strong revenue generation but faces critical challenges in **customer retention** and **product category dependency**. High-value, low-frequency purchases dominate the business model, and over-reliance on a single category poses a risk to sustainable growth.

---

## Technical Skills Demonstrated

- Window Functions (`RANK`, `DENSE_RANK`, `LEAD`, `LAG`, `SUM OVER`)
- Common Table Expressions (CTEs) and Subqueries
- Time-series and trend analysis
- Customer and product segmentation
- Cumulative and part-to-whole analysis
