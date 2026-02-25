# FINANCIAL-ANALYTICS-DASHBOARD
## Recommended Structure and Order
### 📌 Project Overview
The Financial Operations Analytics Dashboard is a SQL-driven business intelligence project designed to analyze revenue performance, customer behavior, churn trends, and revenue concentration across segments and countries.
This project demonstrates strong skills in:
•	SQL Data Cleaning & Transformation
•	Business-Oriented KPI Design
•	Revenue & Customer Analytics
•	Cohort & Churn Analysis
•	Analytical Thinking for Decision-Making
•	Power BI Dashboard Development

### 🎯 Business Objective
The goal of this project was to:<br>
•	Analyze company-wide revenue trends<br>
•	Identify high-performing customer segments<br>
•	Measure churn and retention patterns<br>
•	Evaluate revenue concentration risk<br>
•	Understand payment behavior<br>
•	Generate actionable business insights<br>

### 🛠 Tech Stack
•	SQL (PostgreSQL) → Data cleaning, transformation, and analysis<br>
•	Power BI → Data visualization and dashboard design<br>
•	CSV Datasets → Financial customer & transaction data<br>

### 📂 Dataset Description
The project uses three primary datasets:<br>
**1️. Customers Table**<br>
•	customer_id<br>
•	segment (Small Business, Mid-Market, Startup, Enterprise)<br>
•	country<br>
•	mrr<br>
•	Customer lifecycle data<br>
**2️. Transactions Table**<br>
•	transaction_id<br>
•	customer_id<br>
•	amount<br>
•	transaction_date<br>
•	payment_method<br>
**3️. Monthly Revenue Table**<br>
•	Monthly aggregated revenue values<br>

### 🔎 SQL Analysis Performed
**1️. Data Cleaning**<br>
•	Converted text columns to numeric and date types<br>
•	Handled null values<br>
•	Standardized formats<br>
•	Validated row counts<br>

**2️. Revenue Analysis**
•	Total Revenue Calculation<br>
•	Revenue Trend by Year<br>
•	Revenue by Segment<br>
•	Revenue by Country<br>
•	Revenue by Plan<br>
•	ARPU (Average Revenue per User)<br>
•	Payment Method Distribution<br>

**3️. Customer Analysis**
•	Active vs Churned Customers<br>
•	Monthly Churn Trend<br>
•	Churn by Segment<br>
•	Net Customer Growth<br>
•	Top 10 Revenue Customers<br>
•	Revenue Concentration Analysis<br>

**4️. Advanced SQL Concepts Used**
This project demonstrates strong SQL proficiency including:<br>
•	JOIN operations<br>
•	GROUP BY & Aggregations<br>
•	CASE WHEN logic<br>
•	DATE_TRUNC()<br>
•	Window Functions (NTILE, RANK)<br>
•	CTEs (Common Table Expressions)<br>
•	Subqueries<br>
•	Revenue segmentation logic<br>


## 📈 Dashboard Pages

### 🏠 Overview Page
•	Total Revenue & Transactions<br>
•	Revenue Trend (2020–2024)<br>
•	Revenue by Plan<br>
•	Revenue by Segment<br>
•	ARPU by Month<br>
Insight: Revenue shows steady cumulative growth with moderate expansion rate.

### 👥 Customer Base Page
•	Active Customers<br>
•	New Customers<br>
•	Churned Customers<br>
•	Monthly Churn Trend<br>
•	Churn by Segment<br>
•	Share by Country<br>
•	Net Customer Change<br>
Insight:<br>
•	Small Business contributes highest churn.<br>
•	Customer growth remains positive but churn requires retention focus.<br>

### 💡 Revenue Insights Page
•	Revenue Breakdown (Payment → Segment → Country)<br>
•	Payment Mix Analysis<br>
•	Revenue Concentration (Top 10 Customers)<br>
•	Strategic Business Insights<br>
Insight Highlights:<br>
•	Credit Card dominates payment usage (~60%).<br>
•	Revenue concentration risk exists due to dependency on high-value customers.<br>
•	Enterprise and Small Business segments drive major revenue share.<br>

### 📊 Key Business Insights
✔ Revenue shows stable upward growth trend<br>
✔ Customer growth is steady but churn exists<br>
✔ High revenue dependency on select customer groups<br>
✔ Credit Card is the most preferred payment method<br>
✔ Small Business segment drives major revenue and churn<br>
✔ Business expansion is stable rather than aggressive<br>

### 📌 Business Recommendations
1.	Improve retention strategy for Small Business segment<br>
2.	Diversify revenue base to reduce concentration risk<br>
3.	Introduce incentives for alternative payment methods<br>
4.	Build churn prediction and early warning system<br>
5.	Strengthen engagement campaigns for mid-tier customers<br>


### 📷 Dashboard Preview
### PAGE 1 :- OVERVIEW
![Alt text](https://github.com/AniikettJ/FINANCIAL-ANALYTICS-DASHBOARD/blob/main/SNAPSHOTS/Page%201.png)


### PAGE 2 :- CUSTOMER BASE
![Alt text](https://github.com/AniikettJ/FINANCIAL-ANALYTICS-DASHBOARD/blob/main/SNAPSHOTS/Page%202.png)


### PAGE 3 :- REVENUE INSIGHTS
![Alt text](https://github.com/AniikettJ/FINANCIAL-ANALYTICS-DASHBOARD/blob/main/SNAPSHOTS/Page%203.png)
