# Target Brazil E-Commerce Analysis (SQL Project)

## Project Overview

This project analyzes Target's Brazilian e-commerce operations using SQL. The dataset contains over 100,000 orders placed between 2016 and 2018 and includes information about customers, orders, payments, products, sellers, reviews, and geolocation.

The objective was to uncover business insights related to customer behavior, order trends, logistics performance, payment patterns, and regional market dynamics.

---

## Business Problem

Target wants to better understand:

- Customer purchasing behavior
- Growth trends in order volume
- Regional performance across Brazilian states
- Delivery efficiency and freight costs
- Payment preferences and installment usage
- Opportunities for operational improvement

---

## Dataset

The analysis was performed using a multi-table relational database containing:

- Customers
- Orders
- Order Items
- Payments
- Products
- Sellers
- Reviews
- Geolocation

### Tools Used

- SQL (Google BigQuery)
- Excel (Visualization)
- GitHub

---

## Key Analysis Performed

### 1. Exploratory Data Analysis

- Verified data types and schema structure
- Identified order date range
- Counted customer cities and states

### 2. Order Trend Analysis

- Monthly order growth analysis
- Seasonality investigation
- Customer ordering behavior by time of day

### 3. Regional Performance Analysis

- Month-on-month orders by state
- Customer distribution across states
- State-level sales performance

### 4. Economic Impact Analysis

- Year-over-year payment growth
- Total and average order value by state
- Total and average freight value by state

### 5. Logistics & Delivery Analysis

- Delivery time calculation
- Estimated vs actual delivery comparison
- States with highest and lowest freight costs
- States with fastest and slowest deliveries
- States delivering significantly earlier than estimated

### 6. Payment Analysis

- Payment type trends
- Installment usage patterns
- Customer payment preferences

---

## Major Findings

### Order Growth

- Orders grew steadily throughout 2017.
- Peak order volume occurred in November 2017.
- Monthly order volume remained stable through most of 2018.

### Customer Activity

- Afternoon was the most active purchasing period.
- Dawn recorded the lowest order activity.

### Regional Insights

- São Paulo (SP) dominated customer count and total sales value.
- RJ and MG were the next strongest markets.
- Several northern states showed lower customer penetration but higher average order values.

### Freight Analysis

- SP achieved the lowest average freight costs despite the highest order volume.
- RR, PB, and AC showed significantly higher freight costs.

### Delivery Performance

- Average delivery time was approximately 12.5 days.
- Most orders were delivered earlier than estimated.
- Several states consistently outperformed delivery expectations.

### Payment Behavior

- Credit cards were the dominant payment method.
- Single-installment payments accounted for the majority of transactions.
- Two- and three-installment plans were the next most popular options.

---

## Business Recommendations

### Growth & Marketing

- Focus advertising campaigns during afternoon hours.
- Increase investment in high-performing states such as SP, RJ, and MG.
- Expand customer acquisition efforts in underpenetrated regions.

### Logistics

- Establish regional fulfillment hubs in high-cost freight regions.
- Replicate logistics practices from top-performing states.
- Improve delivery date estimation accuracy.

### Revenue Optimization

- Encourage higher average order values through product bundling.
- Promote 2–3 installment payment options with incentives.
- Improve adoption of alternative digital payment methods.

---

## Repository Structure

```
Target-SQL-Project/
│
├── README.md
├── Target_SQL_Project_Report.pdf
├── SQL_Queries.sql
├── Images/
│   ├── Order_Trend.png
│   ├── Customer_Distribution.png
│   └── Freight_Analysis.png
```

---

## Skills Demonstrated

- SQL Query Writing
- Joins
- Aggregate Functions
- Window Functions
- Common Table Expressions (CTEs)
- Date & Time Analysis
- Business Analytics
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization

---

## Author

**Ajay V Manoj**

Data Science & Machine Learning Student

Email: ajayvm906@gmail.com

---

## Project Report

The complete analysis, SQL queries, outputs, visualizations, insights, and recommendations can be found in:

**Target_SQL_Project_Report.pdf**

