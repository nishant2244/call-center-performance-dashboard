# **Call Center Performance & Sales Intelligence Dashboard**

**An end-to-end Excel solution analyzing operational efficiency—tracking agent performance, revenue generation, and customer sentiment across regional hubs.**

---

## ## Executive Summary

This project transforms raw call center logs and customer data into a strategic **Microsoft Excel**. By merging interaction metrics with transactional outcomes, the dashboard tracks **$96.62K** in revenue while maintaining an average satisfaction score of **3.89**, enabling leadership to optimize staffing and maximize sales conversion.

---

## ## 🛠 Tech Stack & Methodology

* **Microsoft Excel:** The core platform for data modeling and interactive report design.
* **Power Query (ETL):** Standardized disparate datasets, handled null satisfaction values, and mapped representatives (R01–R05) to customer purchase records.
* **DAX (Data Analysis Expressions):** Engineered 10+ custom measures including:
* **Average Duration:** `AVERAGE(Calls[Duration])`
* **Revenue Per Interaction:** `DIVIDE([Total Purchase], [Total Calls])`
* **CSAT Rating:** Calculating weighted satisfaction scores.


* **Data Modeling:** Implemented a **Star Schema** to connect call transactions (Fact Table) with Dimension tables for Geography (Cities), Customers (Demographics), and Time (Fiscal Year).


## ## 📊 Dataset Architecture & Structure

The analysis is grounded in a multi-layered dataset covering **1,000 interactions** with the following key attributes:

* **Transactional Data:** Purchase Amount, Satisfaction Rating, and Call Duration.
* **Customer Profiling:** Segments by **Gender** (Female/Male), **Age**, and **City** (Mumbai, Delhi, Jaipur).
* **Time Intelligence:** Daily and Monthly timestamps to track performance by **Day of Week** and **Fiscal Year (FY)**.
* **Agent Performance:** Metrics categorized by Representative IDs and **Duration Buckets** (e.g., "1 to 2 hours").

---

## ## 💡 Key Business Insights

### 1. Revenue & Regional Hotspots

* **Top Market:** **Mumbai** emerged as the revenue leader with **$37.85K** in sales, followed closely by Delhi ($32.71K).
* **Gender Spend:** Female customers contributed the majority of the bottom line, accounting for **53% ($51.04K)** of total sales.

### 2. Time-Series Trends

* **Peak Performance:** Sales activity spiked significantly on **Saturdays ($16.01K)**, suggesting a need for increased staffing on weekends.
* **Seasonality:** Revenue peaked in **March ($14.56K)** and **April ($13.54K)**, likely correlating with Q1/Q2 marketing campaigns.

### 3. Agent Efficiency

* **High-Value Reps:** **Representative R03** was identified as the top contributor, generating **$20.87K** in revenue.
* **Operational Note:** An average handling time of **89.85 mins** was established as the benchmark for a 3.89/5 satisfaction rating.

---

## ## 🚀 Business Impact

* **Centralized Reporting:** Created a single source of truth for both "Support Quality" and "Sales Performance."
* **Optimized Staffing:** Identified Saturday as the highest-revenue day, allowing for data-driven shift scheduling.
* **Targeted Growth:** Provided demographic insights (Female segment leadership) to help the marketing team refine campaign personas.

---

## ## Dashboard Preview Walkthrough

| Visual Component | Purpose | Key Metric |
| --- | --- | --- |
| **KPI Scorecard** | High-level Health | **Total Sales: $96.62K** |
| **Regional Bar Chart** | Geographic Performance | **Top City: Mumbai** |
| **Monthly Trend (Line)** | Seasonality Identification | **Peak Month: March** |
| **Gender Donut Chart** | Demographic Profiling | **53% Female Revenue** |


## Demo of Project ![Alt text]()
