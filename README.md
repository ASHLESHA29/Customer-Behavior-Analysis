# Customer Behavior Analysis using PostgreSQL & Power BI

## 📌 Project Overview
This project focuses on analyzing customer shopping behavior using **PostgreSQL** for data querying and **Power BI** for dashboard creation and visualization.  
The main objective of this project is to uncover customer purchasing patterns, discount usage, category preferences, seasonal trends, and customer segmentation insights that can help businesses make better data-driven decisions.

This project demonstrates end-to-end **Data Analyst workflow**, including:
- Data exploration
- SQL-based business problem solving
- KPI analysis
- Customer segmentation
- Dashboard development
- Business insights & recommendations

---

## 🎯 Project Objectives
The key objectives of this project were:

- Analyze customer purchase behavior across different product categories
- Identify the most purchased products and categories
- Measure the impact of discounts on customer purchases
- Understand customer frequency and repeat purchase patterns
- Segment customers into meaningful groups
- Build an interactive dashboard in Power BI for business decision-making

---

## 🛠️ Tools & Technologies Used

- **PostgreSQL** – Data storage, cleaning, and SQL analysis
- **pgAdmin 4** – PostgreSQL database management
- **Power BI** – Interactive dashboard and data visualization
- **Excel / CSV** – Dataset source and initial review
- **GitHub** – Project documentation and portfolio hosting

---

## 📂 Dataset Information
The dataset used in this project contains customer shopping-related data such as:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

> **Note:** This dataset was used for educational and portfolio purposes to practice SQL querying, business analysis, and dashboard creation.

---

## 🧹 Data Preparation & Setup

### Steps Performed:
1. Imported the dataset into PostgreSQL
2. Created a database and table structure
3. Loaded customer data into the database
4. Verified column names and data types
5. Connected PostgreSQL database to Power BI
6. Built visualizations based on SQL/business insights

---

## 🗄️ Database Setup (PostgreSQL)

### Database Name
`customer_behavior`

### Example Table Name
`customer`

> **Important Note:** During setup, a trailing space issue in the database name was identified and corrected before connecting to Power BI.

---

## 📊 SQL Analysis Performed

This project includes multiple SQL business questions and insights such as:

### 1. Top Purchased Products
Identified the most frequently purchased products.

### 2. Most Popular Categories
Analyzed which product categories had the highest purchase counts.

### 3. Discount Impact Analysis
Measured which products had the highest percentage of purchases with discounts applied.

### 4. Seasonal Purchase Trends
Studied how customer purchases varied across seasons.

### 5. Location-wise Category Trends
Found top product categories by location/office/region using ranking functions.

### 6. Customer Repeat Behavior
Analyzed repeat customers using purchase frequency and previous purchases.

### 7. Customer Segmentation
Segmented customers into **High Value**, **Medium Value**, and **Low Value** groups based on:
- Total purchase amount
- Previous purchases
- Frequency of purchases

### 8. Payment Method Analysis
Identified preferred payment methods among customers.

### 9. Subscription vs Non-Subscription Behavior
Compared shopping behavior based on subscription status.

### 10. Rating & Review Insights
Explored how customer ratings varied across categories and products.

---

## 💡 Sample SQL Concepts Used

This project demonstrates practical use of:

- `SELECT`, `WHERE`, `ORDER BY`
- `GROUP BY`, `HAVING`
- Aggregate functions: `COUNT()`, `SUM()`, `AVG()`
- `CASE WHEN`
- Window functions:
  - `ROW_NUMBER()`
  - `RANK()`
  - `NTILE()`
- Percentage calculations
- Customer segmentation logic
- Top-N analysis within groups

---
