# Customer-Behaviour-Analysis
An end-to-end data analytics project exploring customer purchasing patterns using Python (Pandas), SQL, and Power BI. The project performs data cleaning, exploratory data analysis, SQL-based business queries, and interactive visualization to uncover actionable insights into customer behavior and purchasing trends.

## Project Overview
The Customer Behavior Analysis Dashboard is a data analytics project aimed at understanding customer purchasing patterns, spending behavior, and product performance.
This project combines SQL, Python (Pandas), and Power BI to extract, clean, analyze, and visualize customer shopping data — transforming raw transactions into business insights that support marketing and sales decisions.

## Business Objective
The objective of this project is to:
1. Understand customer purchasing behavior across demographics and product categories.
2. Identify high-value customer segments and loyalty drivers.
3. Analyze the impact of discounts, shipping methods, and subscriptions on revenue.
4. Present actionable insights through an interactive Power BI dashboard for business stakeholders.

## Tech Stack

| Tool                                     | Purpose                                                 |
| ---------------------------------------- | ------------------------------------------------------- |
| **Python (Pandas)**                      | Data cleaning, transformation, and exploratory analysis |
| **SQL (PostgreSQL / MySQL)**             | Query-based analysis and business logic simulation      |
| **Power BI**                             | Interactive data visualization and dashboard design     |
| **Excel/CSV**                            | Source data format for ingestion and preprocessing      |

## Data Source
The dataset used in this project is:
customer_shopping_behavior.csv
It contains customer-level transactions, including:
 1. Demographics (Gender, Age Group, Location)
 2. Purchase details (Item, Category, Purchase Amount, Discount Applied)
 3. Subscription and Shipping Preferences
 4. Ratings and Purchase History

## Project Workflow
1. **Data Preparation (Python - Pandas)**

Notebook: Customer_Shopping_Behavior_Analysis.ipynb
Tasks performed:
 1. Imported the raw dataset using Pandas.
 2. Handled missing values and formatted inconsistent data.
 3. Transformed data types (dates, numerical, categorical).
 4. Engineered new fields such as:
    Revenue = Purchase Amount * Quantity
    Discount Applied and Customer Segment tags.
    Verified data quality before loading into Power BI and SQL.

2. **Exploratory Data Analysis (Python)**

Performed descriptive statistics and visual analysis to explore:
1. Gender-based revenue differences.
2. Top product categories by purchase amount.
3. Correlation between discount usage and customer loyalty.
4. Average purchase amount by shipping type and subscription status.

📊 Example Visuals:

Distribution of Purchase Amounts.

Category-wise Sales Comparison.

Subscription vs. Average Spending.

3. **Data Analysis (SQL)**

File: customer_behavior_sql_queries.sql

Key queries and insights include:

1. Revenue by Gender — Identified which gender drives higher total sales.
2. Discount Impact — Found customers using discounts but spending above average.
3. Top Rated Products — Discovered 5 products with the highest average ratings.
4. Shipping Comparison — Compared average purchase amounts between Standard and Express shipping.
5. Subscription Analysis — Measured if subscribers spend more and generate higher revenue.
6. Customer Segmentation — Classified customers as New, Returning, or Loyal based on purchase history.
7. Repeat Buyers & Subscription Relationship — Checked if loyal buyers tend to subscribe more.
8. Revenue by Age Group — Revealed which age bracket contributes most to revenue.

4. **Data Visualization & Dashboard (Power BI)**

File: customer_behavior_dashboard.pbix
Built an interactive dashboard with following features:

1. Revenue Overview: Gender, Category, and Age-wise comparison.
2. Top Performing Products: Filterable by category and discount usage.
3. Customer Segmentation: Visualized new, returning, and loyal customer mix.
4. Subscription & Shipping Impact: Compared key business metrics.
5. Dynamic Filters: By region, product category, and customer demographics.

📈 Outcome:
This dashboard serves as a single source of truth for business teams to monitor sales performance, customer loyalty, and marketing effectiveness.

## Business Impact

1. Increased understanding of key revenue drivers and customer retention factors.
2. Helped identify high-performing products and targetable customer groups for marketing.
3. Demonstrated the value of combining SQL logic, Python analytics, and Power BI visualization.
4. Improved decision-making by transforming raw data into clear visual insights.

## Key Insights

1. Female customers generated slightly higher total revenue compared to males.
2. Customers using discounts but still spending above the average were identified as value-driven buyers.
3. Express shipping correlated with higher average order value.
4. Loyal customers accounted for the highest portion of repeat sales and subscriptions.
5. Snacks and Electronics emerged as top-selling product categories.

## Future Enhancements

1. Integrate predictive analytics (e.g., Customer Lifetime Value & Churn Prediction).
2. Automate data refresh in Power BI using scheduled pipelines.
3. Expand SQL logic to support multiple regional databases.
4. Deploy dashboard on Power BI Service or Streamlit for broader accessibility.

## Conclusion

This project demonstrates a complete data analysis lifecycle — from raw data to business insights.
By combining Python for data cleaning, SQL for analytical querying, and Power BI for storytelling, it showcases how data analytics can bridge the gap between business problems and strategic solutions.

