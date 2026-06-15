# Pizza Sales Analysis | SQL + Power BI

##  Project Overview

Analyzed 48,000+ pizza sales records using SQL and Power BI to uncover business insights including revenue trends, peak hours, and best/worst performing pizzas.

##  Tools Used

- **SQL** (MySQL) — Data extraction and analysis
- **Power BI** — Interactive dashboard creation
- **Excel** — Data cleaning and preparation

##  Key Business Questions Answered

1. What is the total revenue generated?
2. What is the average order value?
3. Which pizza category sells the most?
4. Which pizza size is most popular?
5. What are the peak order hours and days?
6. Which are the Top 5 and Bottom 5 pizzas by revenue?

##  Key Insights

- **Total Revenue:** $817.86K
- **Total Orders:** 21,350
- **Total Pizzas Sold:** 49,574
- **Average Order Value:** $38.31
- **Best Selling Category:** Classic (26.91%)
- **Most Popular Size:** Large (45.89%)
- **Peak Days:** Weekends and Fridays
- **Peak Months:** January and July

## Dashboard Preview

**Page 1 — Main Dashboard:**

- KPI Cards (Revenue, Orders, Pizzas Sold, Avg Order Value)
- Daily and Monthly Trend Charts
- Sales % by Category and Size

<img width="609" height="345" alt="Main Dashboard" src="https://github.com/user-attachments/assets/058040aa-dc01-4852-93c2-b8040c9e77e3" />

**Page 2 — Best and Worst Sellers:**

- Top 5 Pizzas by Revenue, Quantity, Total Orders
- Bottom 5 Pizzas by Revenue, Quantity, Total Orders

<img width="623" height="341" alt="image" src="https://github.com/user-attachments/assets/08f3099b-9e76-4767-949b-c98ef840b20a" />

##  SQL Queries Used

- Total Revenue
- Average Order Value
- Total Pizzas Sold
- Total Orders
- Average Pizzas Per Order
- Daily and Monthly Trend for Orders
- Percentage of Sales by Pizza Category
- Top 5 and Bottom 5 Sellers by Revenue, Quantity and Orders

## What I Learned

- Improved my SQL aggregation and filtering skills.
- Learned to create KPI cards and interactive filters in Power BI.
- Practiced turning raw sales data into business insights.

## Challenges Faced

- Accidentally closed MySQL Workbench without saving queries 
  and had to rewrite them from scratch — learned to always 
  save SQL scripts immediately after writing

- Struggled to decide which chart type best represents 
  the data — took multiple attempts before settling on 
  donut charts for category breakdown and line charts 
  for trends

- Connecting SQL query results to Power BI and ensuring 
  the data was accurately reflected in the dashboard

- Deciding correct aggregation (SUM vs COUNT vs AVG) 
  for different business questions — learned that "most 
  popular" and "highest revenue" need completely 
  different approaches

- Designing a clean 2-page dashboard that tells a clear 
  business story without overcrowding visuals

- Figuring out peak hours required extracting HOUR() 
  from order_time — took time to understand time-based 
  functions in SQL

- White space issues inside KPI cards in Power BI 
  took time to fix using padding settings
