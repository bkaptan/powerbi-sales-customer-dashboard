# 📊 Power BI Sales & Customer Analytics Dashboard

This project was developed as part of a **Power BI case study prepared for a job interview process**.  
The goal of this project was to analyze sales and customer data and build an **interactive business intelligence dashboard** that helps stakeholders monitor performance and uncover actionable insights.

The final output is a **Power BI dashboard** designed to provide a clear overview of sales trends, customer acquisition, and category-level performance.

---

# 🚀 Project Overview

Businesses generate large volumes of transactional data every day. However, raw data alone does not provide actionable insights.

This project transforms raw sales data into a **structured analytical model and interactive dashboard** that answers key business questions such as:

- How are sales evolving over time?
- How many **new customers** are acquired each month?
- Which product categories generate the most revenue?
- What trends can be identified in customer purchasing behavior?

The dashboard enables business stakeholders to **quickly monitor performance and make data-driven decisions.**

---

# 📂 Dataset Description

The dataset used in this project contains multiple tables representing different business entities.

### Sales Table
- Sales ID
- Order Date
- Customer ID
- Product ID
- Quantity
- Unit Price
- Discount Rate
- Net Sales
- Order Channel

### Customers Table
- Customer ID
- Customer Name
- Customer Type
- Sector
- City
- Region
- Signup Date
- IsActive

### Products Table
- Product ID
- Product Name
- Category
- Sub Category
- Brand
- Unit Cost
- Unit Price
- IsActive

### Date Table
A dedicated **date dimension table** was created to support time-based analysis.

---

# 🧩 Data Modeling

A **star schema data model** was implemented to optimize analytical performance.

### Fact Table
- Sales

### Dimension Tables
- Customers
- Products
- Date

Relationships were defined between the fact and dimension tables to support efficient filtering and aggregation across analytical dimensions.

Additional **DAX measures** were created to calculate key business metrics such as:

- Total Net Sales
- Total Orders
- Total Sales Quantity
- Average Discount Rate
- Average Order Value
- Top Product Rank
- Bottom 10 Product
- Top 10 Product
- Customer Rank
- Sales Yesterday
- Sales Last Week
- Sales Last Month
- Sales Day Before Yesterday
- Daily Change %
- Discounted Sales %
- MoM Change %
- 

---

# 📈 Dashboard Features

The dashboard was designed to provide both **high-level KPIs and detailed analytical views**.

### KPI Overview
Quick performance summary including:

- Toplam satış performansı
- Aylık satış trendi
- Yeni müşteri kazanımı analizi
- Kategori bazlı satış dağılımı
- Müşteri davranışı analizi

### Sales Trend Analysis
Time-series visualization showing:

- Monthly sales performance
- Growth patterns
- Seasonal trends

### Customer Acquisition Analysis
Analysis of **new customers acquired each month** to track business growth.

### Category Performance Analysis
Revenue distribution across product categories to identify **top-performing categories**.

### Interactive Filters
Users can dynamically filter the dashboard by:

- Date
- Product category
- Customer city segments

---

# 🔍 Key Insights

The dashboard enables the identification of several important business insights, including:

- Monthly fluctuations in sales performance
- Product categories contributing the highest revenue
- Periods with increased customer acquisition rates
- Overall growth trends in sales and customer base

These insights support better **strategic and operational decision-making**.

---

# 🛠 Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**

---

# 🖼 Dashboard Preview

[Dashboard Overview] 
<img width="1341" height="940" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/c3149ce5-e99b-4309-b571-016299a0469d" />


[Sales Analysis]
<img width="1340" height="941" alt="Sales Analysis" src="https://github.com/user-attachments/assets/ffb848e0-f44d-4de6-aa0a-0aa85ba7103a" />


---

# 📁 Repository Structure


