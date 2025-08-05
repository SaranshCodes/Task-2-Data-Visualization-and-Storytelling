# 📊 Sales Dashboard Analysis - Power BI Project

This repository contains a Power BI dashboard project created for analyzing and visualizing sales data from a fictional business scenario.

---

## 📝 Project Overview

The dataset consists of transactional sales data for the year 2023 and includes fields such as:

- Product details (ID, category, cost, price)
- Sales metrics (quantity, sales amount, discount)
- Customer type (New/Returning)
- Region and sales representative
- Sales channel and payment method

The goal of the project was to:
- Clean and prepare the data
- Build a comprehensive and interactive Power BI dashboard
- Derive key business insights from the visualizations

---

## 🔧 Key Steps Performed

1. **Data Cleaning and Preparation**
   - Ensured correct data types for date and numeric fields
   - Created new calculated fields using DAX:
     - `Profit = (Unit_Price * Quantity_Sold * (1 - Discount)) - (Unit_Cost * Quantity_Sold)`

2. **Dashboard Design (Power BI)**
   - Created KPIs for total quantity, sales, average cost, and average price
   - Used various visuals:
     - Line & bar charts for sales trends
     - Pie chart for customer segmentation
     - Treemaps, bar charts, and scatter plots for rep, category, and discount analysis
   - Included slicers for dynamic filtering by Region, Category, Channel, Customer Type, and Payment Method

---

## 🔍 Key Business Insights

1. **Balanced Contribution from Customer Types**  
   Sales are almost equally split between New and Returning customers, showing strong customer retention.

2. **Q3 Achieved the Highest Average Sales**  
   Q3 saw a peak in sales, while Q4 showed a noticeable drop — indicating a seasonal or operational change worth investigating.

3. **High Discounts Are Hurting Profitability**  
   A clear negative correlation exists between discount percentage and profit, especially beyond 20–25%.

4. **All Product Categories Show Negative Profit**  
   Despite revenue, all categories are incurring losses — likely due to pricing, high discounts, or inflated unit costs.

5. **Top Performing Sales Rep**  
   David leads in total sales amount, followed by Eve and Charlie — useful for performance benchmarking.

6. **Online and Retail Channels Perform Similarly**  
   Quantity sold across Online and Retail channels is nearly equal, suggesting a well-balanced omnichannel strategy.

## 📈 Outcome

This project demonstrates how structured dashboards can translate raw sales data into meaningful business insights. It also showcases skills in data wrangling, DAX, visualization, and storytelling with data.

