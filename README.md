# 📊 Coffee Shop Sales Analysis using SQL & Power BI

This project analyzes transactional data from a fictional coffee shop using **SQL** for data transformation and **Power BI** for interactive visualizations. The goal is to uncover valuable business insights, track performance metrics, and explore patterns in customer behavior, product performance, and time-based trends.

---

## 🧠 Project Objectives

- Clean and format raw sales data using SQL
- Calculate monthly KPIs:
  - **Total Sales**
  - **Total Orders**
  - **Total Quantity Sold**
- Perform Month-over-Month (MoM) comparisons and growth calculations
- Analyze:
  - Daily sales trends and average comparisons
  - Sales by **weekday vs. weekend**
  - Store location performance
  - Top-selling product categories and types
  - Hourly sales patterns

---

## 🛠 Tools & Technologies

- **MySQL** – for data preparation and analysis
- **Power BI** – for designing dashboards and visual storytelling
- **Power Query** – for loading and transforming data in Power BI
- **DAX** – for advanced calculations and measures

---

## 📂 Dataset Overview

The dataset includes transactional records with the following key columns:

- `transaction_id`
- `transaction_date` (converted to `DATE`)
- `transaction_time` (converted to `TIME`)
- `store_location`
- `product_category`, `product_type`
- `unit_price`, `transaction_qty`

---

## 📌 Key Insights Delivered

- Daily performance vs. average sales
- Weekday vs. weekend sales distribution
- Top 10 best-selling product types
- Store-wise total sales comparison
- Sales trends by hour of the day
- Month-over-Month growth in sales, orders, and quantity

---

## 📎 Repository Structure

coffee-shop-sales-analysis/
│
├── README.md # Project description
├── coffee_shop_sql_analysis.sql # SQL scripts for data cleaning & analysis
└── powerbi_dashboard/ # (Optional) Power BI file or screenshots


---

## ✅ How to Use

1. Run the SQL script (`coffee_shop_sql_analysis.sql`) on a MySQL-compatible server.
2. Load the cleaned data into Power BI.
3. Use the measures and KPIs to build visualizations.
4. Explore insights or export reports.

---

## 👩‍💻 Author

**Reem Adel Mohamed**  
 Data Analysis Enthusiast

---

## 📬 Contact

For questions or collaboration opportunities, feel free to connect with me on [LinkedIn](www.linkedin.com/in/reem-adel-470a8a2ab) .

---
