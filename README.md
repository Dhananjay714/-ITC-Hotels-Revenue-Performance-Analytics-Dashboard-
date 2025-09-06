# 🏨 ITC Hotels Revenue & Performance Analytics Dashboard  

## 📌 Project Overview  
This project is a **Business Intelligence & Data Analytics solution** built in **Power BI** using a **Kaggle dataset**. It provides a detailed analysis of **Revenue, Occupancy, Room Performance, and Cancellations** for ITC Hotels.  

The dashboard helps hotel management gain insights into:  
- Revenue drivers across properties and room types  
- Occupancy efficiency and booking trends  
- Cancellations and revenue loss impact  

---

## 📂 Dataset  
The dataset used in this project is sourced from **Kaggle**.  

### Files:  
- `dim_hotels.csv` → Hotel master data (hotel IDs, hotel names, categories, locations).  
- `dim_rooms.csv` → Room details (room types, capacities, categories, pricing tiers).  
- `fact_bookings.csv` → Contains individual booking transactions including hotel, room, date, and customer-related metrics.
- `fact_aggregated_bookings.csv` → Aggregated booking data (e.g., daily/monthly summaries). Useful for trend analysis.
- `dim_date.csv` → Date dimension table (day, month, quarter, year, holiday flags, etc.).  
---

## 📊 Dashboard Pages  

### 1️⃣ Financial Overview & Revenue Performance  
- **KPIs:** ADR, MOM Growth %, WOW Growth %, RevPAR, Total Revenue  
- **Charts:** Revenue by Property, Revenue by Room Type, Growth % Trends  

### 2️⃣ Occupancy & Capacity Analysis  
- **KPIs:** Occupancy Rate, WOW Occupancy %, MOM Occupancy %, RevPAR vs Occupancy  
- **Charts:** Occupancy by Property, Occupancy by Room Class, MOM & WOW Trends  

### 3️⃣ Room Performance  
- **KPIs:** ALOS, Booking Lead Time, WOW Occupancy %, MOM Occupancy %  
- **Charts:** Revenue by Date, Revenue by Room Class, ALOS by Hotel & City  

### 4️⃣ Cancellations & Lost Revenue  
- **KPIs:** Cancel Rate, Cumulative Cancellations, Revenue Lost  
- **Charts:** Cancellation Rate by Week, by Room Class, by City & Hotel  

---

## ⚙️ Tools & Technologies Used  
- **Kaggle Dataset** → Source Data (`dim_hotels.csv`, `dim_rooms.csv`,`fact_bookings.csv`,`fact_aggregated_bookings.csv`,`dim_date.csv`)  
- **Power BI** → Dashboard Development & Data Visualization  
- **Power Query** → Data Cleaning & Transformation  
- **DAX** → Measures and Calculations  

---

## 🚀 Key Insights  
✔ Total Revenue crossed **₹2bn** with ADR of **13K**  
✔ **Elite Rooms** generated the highest revenue share (32.79%)  
✔ **ITC Blu** had the highest occupancy rate (62.02%)  
✔ **24.8% Cancellation Rate** led to **₹199M revenue loss**  
✔ Average **Booking Lead Time = 3.71 days**  

---

 ┗ 📄 README.md
