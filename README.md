# Customer Retention & Cohort Analysis

This project analyzes customer behavior using cohort analysis to understand acquisition trends, customer retention, and revenue contribution over time.

By grouping customers based on their first purchase month, we can track how engagement and spending evolve after acquisition and identify opportunities to improve long‑term customer value.

## Dataset

This analysis uses the **Online Retail dataset**, which contains transactional data from a UK-based e‑commerce retailer.

Each row represents a product purchased within a transaction.

### Key Columns

- **InvoiceNo** – Transaction ID  
- **StockCode** – Product identifier  
- **Description** – Product name  
- **Quantity** – Number of items purchased  
- **InvoiceDate** – Timestamp of the transaction  
- **UnitPrice** – Price per item  
- **CustomerID** – Unique identifier for each customer  
- **Country** – Customer location

## Project Structure

The analysis is divided into three main phases:

### Phase 1 — Customer Acquisition Analysis
Understand how many new customers join the platform over time.

### Phase 2 — Customer Retention (Cohort Analysis)
Analyze how many customers return to make purchases after their first purchase.

### Phase 3 — Revenue Retention / Customer Value
Examine how revenue evolves for each cohort and identify which cohorts generate the most value.

# Phase 1 — Customer Acquisition Analysis

### Objective
Analyze how many new customers join the platform each month and identify acquisition trends over time.

Customer acquisition trends help contextualize retention performance and reveal periods of strong or weak growth.

### Key Insights

- Customer acquisition peaked in **December 2010**, likely driven by holiday demand.
- New customer growth declined through mid‑2011 before recovering slightly later in the year.
- Cohort sizes vary significantly across months, suggesting seasonal purchasing patterns or changes in marketing activity.

# Phase 2 — Customer Retention (Cohort Analysis)

### Objective
Evaluate how many customers return to make purchases after their first purchase.

Cohort analysis groups customers by their first purchase month and tracks their activity over time to measure retention behavior.

### Key Insights

- Customer retention drops significantly after the first month, with most cohorts retaining **around 20–40% of customers in month 1**.
- Retention gradually declines in later months, indicating that many customers make only a small number of repeat purchases.
- Early cohorts show slightly stronger long‑term retention compared to later cohorts.

# Phase 3 — Revenue Retention / Customer Value

### Objective
Analyze how revenue from each cohort evolves over time and identify which cohorts generate the most value.

This phase evaluates both **total revenue by cohort** and **average revenue per customer** to better understand customer value.

### Key Insights

- Early cohorts generate the highest total revenue due to their longer activity period.
- Revenue contribution declines over time as fewer customers remain active.
- Average revenue per customer is highest in the early months after acquisition, suggesting customers spend most shortly after their first purchase.

# Executive Summary

This analysis examined customer acquisition, retention, and revenue patterns using cohort analysis.

Customer acquisition was strongest at the beginning of the dataset and declined through mid‑2011 before recovering later in the year.

Retention analysis revealed that customer engagement drops significantly after the first purchase, with most cohorts retaining roughly 20–40% of customers after the first month.

Revenue analysis shows that the majority of customer value is generated in the early months after acquisition, highlighting the importance of encouraging repeat purchases shortly after a customer's first order.

Overall, improving early customer engagement and retention could significantly increase long‑term customer value.

