# Target E-commerce Operations Analysis | SQL

## Project Overview

Analyzed 100,000+ e-commerce orders from Target's operations in Brazil between 2016 and 2018 using SQL. This project explores regional sales performance, order trends, delivery efficiency, freight costs, and customer payment behavior to identify actionable business insights.

## Business Objectives

- Analyze order growth and monthly purchasing trends.
- Evaluate customer distribution and sales performance across Brazilian states.
- Assess order values and freight costs by region.
- Measure delivery times and identify fulfillment bottlenecks.
- Analyze payment methods and installment preferences.
- Recommend improvements in logistics efficiency and customer experience.

## Dataset

The analysis uses eight CSV files:

- `customers.csv` — Customer information and locations.
- `orders.csv` — Order status and purchase and delivery dates.
- `order_items.csv` — Product prices, freight costs, and seller details.
- `payments.csv` — Payment methods, values, and installments.
- `geolocation.csv` — Geographic coordinates and locations.
- `sellers.csv` — Seller information and locations.
- `reviews.csv` — Customer ratings and feedback.
- `products.csv` — Product categories and attributes.

## Tools & SQL Concepts

- SQL
- Common Table Expressions (CTEs)
- Window Functions
- Aggregate Functions
- Joins and Subqueries
- Date and Time Functions
- Grouping and Filtering

## Analysis Performed

### 1. Exploratory Data Analysis
- Examined data types and table structures.
- Identified the order date range.
- Analyzed customer distribution across cities and states.

### 2. Order Trends
- Evaluated yearly and monthly order growth.
- Identified monthly seasonality.
- Analyzed order patterns by time of day.

### 3. Regional Sales & Economic Impact
- Compared customer distribution across Brazilian states.
- Calculated total and average order values by state.
- Evaluated freight costs across regions.
- Analyzed year-over-year changes in order payment values.

### 4. Delivery & Logistics Performance
- Calculated order delivery times.
- Compared estimated delivery dates with actual delivery dates.
- Identified states with the highest and lowest average freight costs.
- Compared delivery performance across states.

### 5. Payment Analysis
- Analyzed monthly orders by payment method.
- Examined customer payment installment preferences.

## Business Value

The analysis uses SQL to derive insights that can support:

- Regional sales and fulfillment planning.
- Freight-cost optimization.
- Delivery performance improvement.
- Payment strategy evaluation.
- Better customer experience.
