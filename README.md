#  Zomato Delivery Operations Analytics

## 📊 Project Overview
This project analyzes the **Zomato Delivery Operations dataset** (from Kaggle) to explore delivery efficiency, courier productivity, and the impact of traffic and weather conditions on operations.  
The goal is to identify bottlenecks, confirm or reject business hypotheses, and provide actionable recommendations.

---

## 📂 Dataset
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/saurabhbadole/zomato-delivery-operations-analytics-dataset)  
- **Format**: CSV  
- **Size**: ~45k rows raw → ~33k rows after cleaning  
- **Key columns**:  
  - `Order_Date`, `Time_taken (min)`  
  - `Delivery_person_ID`, `Delivery_person_Age`, `Delivery_person_Ratings`  
  - `City`, `Road_traffic_density`, `Weather_conditions`, `Festival`  
  - `Type_of_order`, `Type_of_vehicle`, `multiple_deliveries`  

---

## ❓ Analytical Questions
1. What is the **average delivery time** across different cities?  
2. How does **road traffic density** affect delivery time?  
3. Does **weather condition** increase or decrease delivery time?  
4. Do **festivals** impact delivery operations?  
5. Which **order types** (Meals, Snacks, Drinks, Buffet) are the most popular?  
6. Which **couriers** deliver the most orders? (Top-20 productivity)  
7. Is there a relationship between **courier ratings** and delivery time?  
8. How does **Order Throughput** change depending on **Traffic and Weather**?  

---

## 🛠 Methods & Tools
- **Python (Pandas)**:  
  - Data cleaning (datetime conversion, drop missing values, duplicates removed)  
  - Exploratory analysis and aggregations   
- **Tableau**:  
  - Dashboard design & interactive visualization  

---

## 📈 Visualizations
- KPI Cards: Total Orders, Avg Delivery Time, Avg Courier Rating  
- Orders Trend (line chart)  
- Order Throughput (orders per courier)  
- Heatmap: Traffic × Weather → Avg delivery time  
- Orders by City (bar chart)  
- Order Types Popularity (bar chart)  
- Festival vs Non-Festival Comparison  
- Top Couriers Productivity  
- Delivery Location Heatmaps (orders volume & avg time)  

---

## 🔑 Insights
- **Metropolitan** cities have the highest order volume but also the longest delivery times.  
- **Jam traffic + Stormy weather** cause the most severe delivery delays.  
- **Festivals** increase delivery time by ~15–20%.  
- **Meals** are the most popular order type, but they take longer than Drinks/Snacks.  
- **Top-5 couriers** deliver 2–3x more orders than average.  

---

## ✅ Recommendations
- Recruit additional couriers in Metropolitan areas during festivals.  
- Implement bonus incentives for couriers working in **Jam traffic** conditions.  
- Optimize courier routing under **stormy weather** (predictive delays).  
- Encourage high-performing couriers with reward systems to improve retention.  

---

## 🔗 Deliverables
- 📊 Tableau Dashboard: [https://public.tableau.com/views/tableaufinal_17594802516990/operationalmetrics?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link](#)  
- 📂 Clean Dataset: [https://docs.google.com/spreadsheets/d/1Appr7bzHoORPmMO3xxyLC8THIxe3UdZuWH0Is7Ifbws/edit?usp=sharing](№)

---

📅 *Final Project — Data Analytics Course*  
