# 🐧 Penguin Coffee Sales Dashboard – 2023 Half-Year Review  

## Overview  
The **Penguin Coffee Sales Dashboard** delivers a mid-year performance review for Penguin Coffee’s **Sydney Sales Region**, covering three flagship stores: **Newtown, Bankstown, and North Sydney**. Developed in **Power BI**, this interactive report enables stakeholders to track KPIs, explore customer behavior, optimize store operations, and forecast full-year revenue based on current trends.  

Built for business leaders and operations teams, the dashboard tells a cohesive story—from high-level KPIs to granular performance by **product, category, store location, and time of day**.  

---

## Purpose  
As Penguin Coffee expands across Sydney, leadership required a comprehensive analytics dashboard to answer key business questions:  

- What are our **core performance metrics** for 2023 so far?  
- Which **products and categories** are driving revenue?  
- Which **time slots** generate the most sales?  
- How can we **streamline store operations**?  
- What are the **sales projections** for the remainder of the year?  

This dashboard acts as a **central decision-making tool** to guide promotional strategies, staffing schedules, and inventory planning.  

---

## Dataset  
The dataset contains over **149,000 transaction records** across three Sydney stores. Key data includes:  

- **Sales transactions**: Quantity, time, order value, store  
- **Product details**: Category, item type  
- **Customer behavior**: Purchase timing patterns  
- **Store info**: Location-based performance  

The data model follows a **star schema** with clearly defined dimensions and fact tables:  
- `Product_Dim`  
- `Store_Dim`  
- `Date_Dim`  
- `Forecast_Date_Table`  
- `Penguin_Koffee_Fact` (central fact table)  

---

## Tools Used  
- **Power BI**: Data modeling, DAX calculations, and interactive visuals  
- **Power Query**: Data cleaning and transformation  
- **DAX**: KPI calculations, forecasting, and time intelligence  
- **Forecasting Techniques**: Built-in Power BI forecasting to project full-year revenue  

---

## Dashboards  
![Dashboard 1](https://github.com/user-attachments/assets/7443e3dc-663f-4c55-9e03-d08cfd5a172b)  
![Dashboard 2](https://github.com/user-attachments/assets/10b08570-ef2f-4f3c-92ea-a91995ce9c9f)  
![Dashboard 3](https://github.com/user-attachments/assets/b624fbb5-9ce6-4e3f-8db5-9ec9cc4376df)  

---

## Key Dashboard Sections  

### 1. Executive Summary (Top Cards)  
- **Total Sales**: $698,812  
- **Transactions**: 149,116  
- **Avg. Order Size**: $4.69  
- **Best-Selling Items**: *Crow’s Nest Croissant* (quantity), *Davy Jones’ Organic Hot Chocolate* (revenue)  
- **Store Expansion**: 3 new locations  

---

### 2. Sales by Product & Category  
- **Coffee** leads with **38.6% of total sales**, followed by Tea and Bakery  
- Ranks **top 10 products** by revenue and quantity  
- Store-level insights highlight location-specific product preferences  

---

### 3. Time of Day Revenue Analysis  
- Peak sales occur between **9 AM – 11 AM**, with **10 AM** as the top revenue hour  
- Minimal sales **before 7 AM and after 7 PM** (3.6% of total revenue)  
- Insights can inform **store hours and staffing schedules**  

---

### 4. Forecasting Full-Year Revenue  
Based on Jan–Jun 2023 data, projected total revenue: **$1.4M**  
- **Bankstown**: $476,942  
- **Newtown**: $463,928  
- **North Sydney**: $468,337  

Forecasts reflect **upward trends in May–June**, driven by growth in order size and transaction volume.  

---

## Recommendations  
- Align **opening/closing hours** with peak customer traffic to optimize labor costs  
- Promote top-performing products, especially **coffee and specialty drinks**  
- Analyze underperforming time slots and test promotions to boost off-peak traffic  
- Use store-specific insights to **customize inventory and marketing strategies**  
- Track month-over-month trends to refine forecasting assumptions and reforecast quarterly  
