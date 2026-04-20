# 🛒 Superstore Sales Analysis

## Project Overview
This project performs a full exploratory data analysis (EDA) on the **Sample Superstore** dataset — a commonly used retail dataset containing ~10,000 orders across product categories, regions, and customer segments in the United States (2014–2017).

## Dataset
| Attribute | Value |
|-----------|-------|
| File | `Sample_-_Superstore.csv` |
| Rows | 9,994 |
| Columns | 21 |
| Date Range | January 2014 – December 2017 |
| Key Fields | Order Date, Category, Sub-Category, Region, Segment, Sales, Profit, Discount |

## Notebook Structure

| Task | Description |
|------|-------------|
| **Task 1** | Load & Explore — `df.head()`, `df.info()`, `df.describe()` |
| **Task 2** | Data Cleaning — missing values, date conversion, Postal Code fix |
| **Task 3** | Feature Engineering — Month/Year extraction, Profit Margin column |
| **Task 4** | GroupBy & Aggregation — sales by category, profit by region, top customers, monthly trends |
| **Task 5** | Pivot Tables — Category × Region, Segment × Year, Sub-Category profit |
| **Task 6** | Splitting & Merging — Orders / Customers / Products split, then merged back |
| **Task 7** | Visualisation — line chart, bar charts, pie chart |
| **Task 8** | Insights & Conclusions |

## Key Findings
1. **Technology** is the top-revenue category ($836K), while **Office Supplies** leads on profit margin.
2. The **Central region** underperforms in profitability despite healthy sales.
3. **Tables** and **Bookcases** are the only sub-categories with *negative* total profit — a result of aggressive discounting.
4. Sales exhibit a consistent **Q4 peak** each year, driven by holiday and year-end purchasing.
5. The **Consumer** segment accounts for ~50% of all sales.
6. Discounts above **30%** almost universally result in a loss on individual orders.

## Requirements
```
pandas
numpy
matplotlib
```

## How to Run
```bash
# Place Sample_-_Superstore.csv in the same directory as the notebook, then:
jupyter notebook Superstore_Analysis.ipynb
```
