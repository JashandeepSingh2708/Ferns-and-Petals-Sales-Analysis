# Ferns-and-Petals-Sales-Analysis
A comprehensive Excel dashboard project analyzing Ferns and Petals (FNP) sales data using Power Query, Power Pivot, and Pivot Tables. This interactive report uncovers trends in revenue, customer spending, product performance, and delivery time across various occasions and cities.

# 🌼 FNP Sales Analysis Excel Dashboard

Welcome to the **Ferns and Petals (FNP) Sales Analysis** project – a complete Excel dashboard built using **Power Query**, **Power Pivot**, and **Pivot Tables**. This project is aimed at helping FNP analyze sales, customer behavior, and product trends across various gifting occasions.

---

## 📌 Project Objective

FNP (Ferns and Petals) is an online gifting platform that delivers gifts across India for festivals and personal occasions like **Anniversaries, Birthdays, Raksha Bandhan, Diwali, and Valentine's Day**.

This project analyzes:
- Revenue trends
- Top-selling products
- Monthly and hourly order patterns
- Customer spending behavior
- Occasion-wise and city-wise performance

---

## 🔧 Tools & Techniques Used

| Feature        | Description |
|----------------|-------------|
| **Power Query**     | Data cleaning, merging tables (orders, products, customers), calculated columns |
| **Power Pivot**     | Data modeling using relationships (ProductID, CustomerID) |
| **Calculated Columns** | Order Time, Delivery Time, Hourly/Monthly breakdowns |
| **Pivot Tables**     | Used for aggregations by month, product, city, occasion |
| **Pivot Charts & Slicers** | Interactive visuals for dynamic filtering and analysis |

---

## 📊 Key Dashboard Insights

### 🟢 Top KPIs:
- **Total Orders**: 1000  
- **Total Revenue**: ₹35,20,984  
- **Avg. Order-Delivery Time**: 5.53 days  
- **Avg. Customer Spend**: ₹3,520.98  

### 🗓️ Monthly Sales Trends:
- Highest revenue: **July & February**
- Lowest activity: **May & June**

### 🎁 Top 5 Products by Revenue:
- Mugham Set
- Quib Gift
- Dadora Gift
- Harum Pack
- Dessert Box

### 🏙️ Top 10 Cities by Orders:
- Delhi, Indore, Gurgaon, Mumbai, Noida, etc.

### 🎉 Revenue by Occasion:
- Highs: Anniversary, Raksha Bandhan, Holi  
- Lows: Valentine's Day, Birthday

### ⏱️ Order Time Analysis:
- Order and delivery times broken down by **hour of day**

---

## 📂 Data Model & Structure

- **orders**: Includes order IDs, dates, customer ID, product ID, quantity
- **products**: Product name, category, price
- **customers**: Customer demographics (optional if included)

### ➕ Created Columns:
- `Revenue` = Quantity × Product Price (merged from product table)
- `Order Hour`, `Delivery Hour` for time-based trend analysis
- `Order Day Name`, `Order Month` for visual filters
- `Occasion` mapping for categorical analysis

---

## 📸 Dashboard Preview

![image](https://github.com/user-attachments/assets/06a4714b-4834-4182-add2-d081989ea467)



---

