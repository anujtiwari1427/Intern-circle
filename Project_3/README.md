# InternCircle Project 03 — Customer Churn / Sales Trend Analysis

## Project overview
This project performs an end-to-end analysis of a simulated e-commerce orders dataset to identify monthly revenue trends, best-performing categories, and high-value customers.

## Dataset
- Generated sample data (not real customer data)
- 2,000 order records
- 300 possible customer IDs
- Date range: 2025-01-01 to 2025-12-31
- Categories: Electronics, Fashion, Home, Books
- Fixed random seed: 42

## Main analysis
1. Data checks: shape, types, missing values, duplicates.
2. Date feature engineering: month, weekday, quarter.
3. Monthly revenue and month-over-month growth using `pct_change()`.
4. Category totals, average order value, order count, and month-by-category pivot table.
5. Customer spend and top 10% revenue share (Pareto-style analysis).
6. Business recommendations based on computed results.

## Key results from this generated sample
- Total revenue: 2,404,233.29
- Average order value: 1,202.12
- Best month: 2025-02 (232,027.20)
- Lowest month: 2025-08 (179,783.75)
- Highest-revenue category: Fashion (35.5% of revenue)
- Top 10% of customers contribute 18.9% of revenue

## How to run
1. Install: `pip install pandas numpy matplotlib seaborn jupyter`
2. Open `Project_03_Sales_Trend_Analysis.ipynb` in Jupyter or Google Colab.
3. Run all cells from top to bottom.
4. The notebook exports CSV summaries and `sales_analysis_dashboard.png`.

## Submission items
- Notebook: `Project_03_Sales_Trend_Analysis.ipynb`
- One-page brief: `Project_03_Business_Brief.pdf`
- Dashboard: `sales_analysis_dashboard.png`
- Dataset and CSV analysis outputs.
