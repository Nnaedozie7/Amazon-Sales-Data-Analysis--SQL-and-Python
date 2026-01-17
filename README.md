# Amazon Sales Data Analysis (SQL & Python)

This project analyzes **Amazon global sales data** using **SQL (SQLite)** and **Python** to uncover insights related to revenue, profit, product performance, regions, sales channels, and order priorities.

The analysis demonstrates practical use of **SQL queries**, database creation, and data exploration for business intelligence and data analytics purposes.

---

## 📌 Project Overview

The objective of this project is to:
- Store structured sales data in a relational database
- Perform SQL-based exploratory analysis
- Analyze revenue, profit, and units sold across multiple dimensions
- Identify high-performing regions, countries, and product categories
- Understand sales behavior based on channel and order priority

The project integrates **Python and SQLite** to simulate a real-world data analytics workflow.

---

## 📊 Dataset Description

The dataset contains **1,000 sales records** with the following key attributes:

- `Region`
- `Country`
- `Item Type`
- `Sales Channel` (Online / Offline)
- `Order Priority` (H, M, L, C)
- `Order Date`
- `Ship Date`
- `Order ID`
- `Units Sold`
- `Unit Price`
- `Unit Cost`
- `Total Revenue`
- `Total Cost`
- `Total Profit`

The data covers multiple regions including:
- Sub-Saharan Africa
- Europe
- Asia
- Australia and Oceania
- Middle East and North Africa
- North America
- Central America and the Caribbean

---

## 🛠️ Tools & Technologies

- **Python**
- **SQLite**
- **SQL**
- **Pandas**
- **Jupyter Notebook**

---

## 🗄️ Database Design

- A SQLite database (`Amazon.db`) was created
- Sales data was imported from CSV into a table named `Amaz`
- Column data types were validated using `PRAGMA table_info`

This setup enables efficient querying and structured analysis.

---

## 🔍 Analysis Performed

### 📈 Revenue & Profit Analysis
- Total revenue and profit by:
  - Country
  - Region
  - Item Type
- Identification of top and bottom performing countries

### 📦 Product Performance
- Revenue, profit, and units sold by item type
- Profit margin (%) calculated for each product category
- Comparison of high-margin vs high-volume products

### 🌍 Regional Insights
- Regional contribution to total revenue and profit
- Product performance within each region

### 🛒 Sales Channel Analysis
- Comparison of Online vs Offline sales
- Distribution of sales channels by region and product type

### 🚦 Order Priority Analysis
- Distribution of order priorities across:
  - Item types
  - Regions
  - Countries

### ⏱️ Delivery Time
- Estimated delivery time calculated using:
