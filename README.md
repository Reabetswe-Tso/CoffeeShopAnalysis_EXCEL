# Coffee Shop Sales Analysis using Excel

![](https://your-repo-link/logo.png)

## Overview
This project presents a comprehensive analysis of a coffee shop’s sales data using Microsoft Excel. The goal is to uncover performance trends, customer behavior, and product profitability through data cleaning, visualization, and formula-driven insights. This README outlines the project’s objectives, business problems, solutions, findings, and conclusions.

## Objectives

- Clean and structure raw transactional data for analysis.
- Build dynamic dashboards to visualize key performance indicators.
- Identify top-selling products and peak sales periods.
- Segment customers and analyze purchasing behavior.
- Automate calculations for revenue, cost, and profit margins.

## Dataset

The dataset contains transactional records from a coffee shop, including product details, sales dates, customer information, and financial metrics.

- **Dataset Source:** Internal business records (Excel format)

## Schema

| Column Name       | Description                                 |
|-------------------|---------------------------------------------|
| Transaction ID    | Unique identifier for each sale             |
| Date              | Date of transaction                         |
| Product           | Item sold (e.g., Latte, Muffin)             |
| Category          | Product category (e.g., Beverage, Food)     |
| Quantity          | Number of units sold                        |
| Unit Price        | Price per unit                              |
| Total Revenue     | Quantity × Unit Price                       |
| Cost              | Cost of goods sold                          |
| Profit            | Revenue minus cost                          |
| Customer Segment  | Type of customer (e.g., Regular, New)       |

## Business Problems and Solutions

### 1. Identify Top 5 Products by Revenue

**Objective:** Determine which products generate the most income.

**Solution:** Use a pivot table to sum revenue by product and sort descending.

### 2. Analyze Monthly Sales Trends

**Objective:** Understand seasonal patterns and monthly performance.

**Solution:** Group data by month and visualize with a line chart.

### 3. Highlight Low-Profit Items

**Objective:** Flag products with low profit margins.

**Solution:** Use conditional formatting to highlight profit < 10%.

### 4. Compare Category Performance

**Objective:** Evaluate which product categories drive sales.

**Solution:** Use a bar chart to compare total revenue by category.

### 5. Segment Customers by Spending

**Objective:** Classify customers into high, medium, and low spenders.

**Solution:** Use IF statements and COUNTIFS to categorize based on total spend.

### 6. Detect Anomalies in Pricing

**Objective:** Spot outliers in unit price or quantity sold.

**Solution:** Use AVERAGE, STDEV, and Z-score logic.

### 7. Automate Profit Calculation

**Objective:** Ensure consistent profit computation.

**Solution:** Formula: `=Quantity * Unit Price - Cost`

### 8. Build Interactive Dashboard

**Objective:** Provide stakeholders with a dynamic view of KPIs.

**Solution:** Combine pivot charts, slicers, and summary cards.

## Findings and Conclusion

- **Top Products:** Beverages dominate revenue, with seasonal spikes in specialty drinks.
- **Customer Segments:** Regular customers contribute the majority of revenue.
- **Profitability:** Some food items have low margins despite high sales volume.
- **Sales Trends:** Weekends and holidays show peak performance.

This Excel analysis equips the coffee shop with actionable insights to optimize inventory, pricing, and customer engagement strategies.
