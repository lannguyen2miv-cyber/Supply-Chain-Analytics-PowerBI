# Supply-Chain-Analytics-PowerBI
End-to-End Supply Chain Analytics Project using SQL and Power BI with interactive dashboards and business insights.
# Supply Chain Analytics Dashboard

> End-to-End Business Intelligence Project using **SQL**, **Power BI**, and **Business Storytelling** to analyze global supply chain performance, sales trends, inventory, and logistics operations.

## Project Overview

This project analyzes more than **180,000 supply chain orders (2015–2018)** from a global retail company.
The objective is to transform raw transactional data into business insights through SQL data preparation, interactive Power BI dashboards, and data-driven recommendations for Supply Chain and Marketing teams.
The project simulates how a Business Intelligence Analyst supports operational decision-making across multiple business functions.

##  Business Objectives

The dashboard helps answer the following business questions:

  ### Supply Chain
- How has order volume changed over time?
- Does higher order volume increase late delivery risk?
- Which departments generate the highest number of late deliveries?
- Which product categories contribute most to delayed shipments?
- Which shipping modes perform better?
- What is the gap between scheduled shipping days and actual shipping days?
- Which order statuses dominate operational performance?
  ###  Marketing & Sales

- Which customer segment generates the highest revenue?
- Which markets contribute the most sales?
- Which departments drive overall sales?
- Which product categories contribute the highest revenue?
- How do sales, discounts and profits evolve over time?
- Which departments offer the best balance between sales and profitability?

## Dataset

Source:

**DataCo Global Supply Chain Dataset**

- 180,519 Orders
- 4 Years (2015–2018)
- Global Markets
- Multiple Departments
- Multiple Customer Segments

Main dimensions

- Customer
- Product
- Department
- Geography
- Shipping
- Time

---

## Data Preparation (SQL)

The dataset was cleaned using SQLite.

Main transformations include:

- Removing invalid records
- Removing duplicate Order Item IDs
- Renaming columns
- Creating Quarter_Year field
- Standardizing date formats
- Optimizing data types
- Creating indexes for faster queries

##  Power BI Dashboard

Main KPI Cards

- Total Orders
- Total Sales
- Total Discount
- Total Profit
- Average Scheduled Shipping Days
- Average Actual Shipping Days

Interactive Filters

- Quarter
- Customer Segment
- Market
- Shipping Mode


## Dashboard Storytelling

The dashboard follows a business storytelling approach.

Step 1 Understand overall business performance through KPI cards.
↓
Step 2 Observe customer and market distribution.
↓
Step 3 Analyze sales trends over time.
↓
Step 4 Deep dive into departments with the highest sales or operational issues.
↓
Step 5 Identify product categories driving business performance.

↓
Step 6 Generate business recommendations.

##  Key Business Insights

Examples

- Higher order volume does not always lead to higher late delivery.
- Fan Shop and Apparel generate the largest operational workload.
- Standard Class accounts for the largest shipment volume.
- Europe and LATAM contribute the highest revenue.
- Several departments maintain high sales but relatively lower profitability.
## Business Recommendations
Supply Chain
- Optimize fulfillment for high-volume departments.
- Rebalance shipping capacity during peak quarters.
- Improve SLA monitoring.
- Reduce delays through shipping mode optimization.
Marketing
- Focus campaigns on high-profit customer segments.
- Allocate budget toward high-performing markets.
- Review discount strategies for low-profit categories.
