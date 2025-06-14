# ☕ Maven Roasters Sales Performance Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow?style=for-the-badge&logo=powerbi)
![Excel](https://img.shields.io/badge/Excel-Data%20Cleaning-green?style=for-the-badge&logo=microsoft-excel)
![License](https://img.shields.io/badge/LICENSE-MIT%20-blue?style=for-the-badge&logo=MIT)

## 📌 Project Overview
This project provides a **comprehensive analysis of sales performance** for **Maven Roasters**, a coffee shop franchise operating in **New York City** across three locations: **Lower Manhattan, Hell’s Kitchen, and Astoria**. The goal was to analyze transactional data over **six months (January – June 2023)** to uncover customer purchasing behaviors and optimize business operations.

## 📊 Key Objectives
✔️ Develop a **Sales Overview** to assess revenue distribution.  
✔️ Analyze **Monthly Sales Trends** to identify seasonal patterns.  
✔️ Investigate **Customer Purchasing Behaviors** to understand peak sales periods.  
✔️ Provide **Data-Driven Business Recommendations** for operational efficiency.  

## 🗂 Dataset Overview
Link: https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales

The dataset contains **149,116 transaction records** with **11 key attributes**:
- **Integer:** `transaction_id`, `transaction_qty`, `store_id`, `product_id`
- **Float:** `unit_price`
- **Date & Time:** `transaction_date`, `transaction_time`
- **Text:** `store_location`, `product_category`, `product_type`, `product_detail`

## 🔍 Analysis Process
Refer: Sales Performance Analysis of Maven Roasters REPORT.pdf
### 1️⃣ **Data Cleaning & Preparation**
- Standardized product names and resolved inconsistencies.
- Created a **Date Table** for time-based filtering.
- Performed **DAX Calculation** for advanced calculations and KPIs.

### 2️⃣ **Data Modeling**
- Linked **Transactions Table** with the **Date Table** via `transaction_date`.
- Created measures to analyze sales trends and revenue share.
<img src="https://github.com/user-attachments/assets/2a92fdd8-2c02-43dc-a84c-1131415823cf" width="600" height="300">

### 3️⃣ **Exploratory Data Analysis (EDA)**
- **Total Sales:** `$698,812` across **214,470 units sold**.
- **Top Locations:** Hell’s Kitchen contributed **33.84%** of total revenue.
- **Best-Selling Categories:** 
  - Coffee ☕ **($270K, 38.6%)**
  - Tea 🍵 **($196K, 28%)**
  - Bakery 🥐 **($82K, 11.7%)**

### 4️⃣ **Customer Purchasing Patterns**
- **Peak Hours:** **7:00 AM – 11:00 AM** (highest transaction volume).
- **Busiest Days:** **Mondays, Tuesdays, and Fridays**.

## 📈 Data Visualization
An **interactive Power BI dashboard** was created to showcase:

✅ **KPI Cards** for performance tracking.  
✅ **Trend Charts** for monthly sales growth.  
✅ **Pie Charts** for store revenue contribution.  
✅ **Bar Charts** for product category analysis.

<img src="https://github.com/user-attachments/assets/aad366d4-98b7-4dd0-aae9-142a974c515e" width="800" height="500">


## 📢 Business Recommendations
💡 **Optimize Inventory**: Maintain high stock levels for best-sellers like Coffee & Tea.  
💡 **Expand Operations**: Increase capacity in Hell’s Kitchen due to high footfall.  
💡 **Dynamic Pricing**: Adjust pricing based on peak hours and demand trends.  
💡 **Upselling Strategies**: Bundle slow-selling items with popular products.  
💡 **Enhance Service Efficiency**: Introduce **mobile ordering** and **express pickup** to reduce wait times.

## 🛠 Tech Stack
- **📊 Power BI** – Interactive dashboard development
- **📈 Excel** – Data cleaning and pre-processing

## 📌 Future Enhancements
🔹 Incorporate **Machine Learning** to predict future sales trends.  
🔹 Expand analysis to include **customer demographics** and retention strategies.  
🔹 Develop a **real-time analytics dashboard** for live data monitoring.  

## 🤝 Contributing
We welcome contributions! Feel free to **fork** this repository, submit **pull requests**, or raise **issues** for improvements.

## 📜 License
This project is licensed under the **MIT License** – free to use and modify.

## 🌟 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mohammad-adnan-mohiyaddin/?trk=opento_sprofile_details)  
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/ADNAN-BAVA)

