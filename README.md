# Olist E-Commerce Performance: Revenue & Product Quality Analysis

## Project Overview
This project analyzes a real-world Brazilian e-commerce dataset by Olist (containing over 100k anonymized orders) to uncover actionable business insights. The primary objective is to evaluate product performance by identifying top revenue-generating categories, assessing product quality through customer satisfaction metrics, and analyzing consumer payment behaviors. 

By bridging data wrangling in Python with interactive visualization in Tableau, this analysis provides a strategic overview for management to optimize marketing budgets and evaluate supplier quality.

## 📊 Tableau Dashboard
**Interact with the full dashboard here:** https://public.tableau.com/views/OlistE-CommerceRevenueProductQualityAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

*(Optional: You can add a screenshot of your Tableau dashboard here by dragging and dropping an image file into GitHub)*
`![Dashboard Screenshot](link-to-your-image.png)`

## 🛠️ Tools & Technologies Used
* **Python (Pandas):** Data cleaning, handling missing values, dropping duplicates, merging multiple datasets (Row Explosion prevention strategy), and aggregating data based on statistical significance.
* **Jupyter Notebook:** Step-by-step code documentation and exploratory data analysis (EDA).
* **Tableau Public:** Interactive data visualization, dual-axis donut charts, KPI scorecards, and time-series analysis.

## 📈 Key Business Insights
Based on the dashboard and data analysis, here are the main findings:
1. **Top Revenue Drivers:** The [Insert Top Category 1] and [Insert Top Category 2] categories are the financial backbone of the company, generating the highest total revenue among all product lines.
2. **Product Quality Concerns:** When filtering for statistical significance (categories with >50 reviews), [Insert Worst Category] and [Insert 2nd Worst Category] emerged with the lowest average customer ratings, indicating systemic quality or expectation-matching issues.
3. **Revenue Trends:** The time-series analysis indicates a [Insert Trend, e.g., steady growth / seasonal spike] in total sales during [Insert Month/Year], highlighting key periods for consumer demand.
4. **Payment Preferences:** The majority of transactions are completed via [Insert Top Payment Method, e.g., Credit Card] representing [Insert %]% of total sales volume, indicating a strong consumer preference for installment or cashless payments.

## 💡 Actionable Recommendations
* **Marketing Optimization:** Allocate a larger portion of the digital marketing budget toward the top 3 revenue-generating categories to maximize Return on Ad Spend (ROAS).
* **Supplier Audit:** Management must initiate an immediate quality-control review of the suppliers providing goods in the lowest-rated categories. If the low ratings are driven by product defects rather than logistics, replacing these suppliers is critical to preventing customer churn.
* **Payment Promotions:** Since [Insert Top Payment Method] dominates the revenue stream, partnering with those specific financial providers for exclusive discounts or cashback campaigns could further boost conversion rates.

## 📂 Repository Structure
* `olist_revenue_quality_analysis.ipynb`: The main Python script containing the complete data wrangling, merging, and aggregation processes.
* `cleaned_olist_sales_data_v2.csv`: The cleaned and aggregated dataset used as the data source for the Tableau dashboard. (Note: Original raw datasets are excluded due to file size limits).

---
*Prepared by Athaariq Alifsyah
