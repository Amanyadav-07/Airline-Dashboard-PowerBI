# ✈️ Airline Data Management and Analysis Using Power BI

This project is part of the **Data Science PGC C3 Final Project** submission, where I analyzed and visualized airline operations data using **Microsoft Power BI**. The goal was to extract meaningful insights from raw flight, ticket, and passenger datasets and present them in an interactive, professional dashboard.

---


---

## 📁 Project Overview

The project involved multiple phases of a real-world analytics workflow:

### 🔹 1. Data Preparation & Cleaning
- Removed nulls, duplicates, and blanks
- Renamed columns and ensured proper data types
- Used **Power Query** for transformation

### 🔹 2. Data Modeling
- Built relationships across 3 datasets using `FlightID`
- Applied one-to-many and many-to-one cardinalities
- Created a unified star schema

### 🔹 3. Enhanced Data Insights
- Added conditional columns (`FlightStatusLabel`)
- Extracted flight numbers using "Column from Examples"
- Labeled flights as **Best** or **To Be Improved**

### 🔹 4. DAX Calculations
- Calculated:
  - Total passengers for a specific flight
  - Total confirmed tickets
  - A filtered table for Best Flights
- Used `CALCULATE()`, `COUNTROWS()`, and `FILTER()` functions

### 🔹 5. Visualization and Interactivity
- Interactive dashboard built with:
  - Donut Chart (Ticket Status)
  - Bar Chart (Passenger Count by Airline)
  - Matrix (Flights by Destination)
  - Cards (KPIs)
  - Slicers (Airline, Destination)
- Fully interactive visuals with real-time filtering

### 🔹 6. Deployment on Power BI Service
- Dashboard published to [Power BI Service]([https://app.powerbi.com/](https://app.powerbi.com/groups/me/reports/e8103f90-85a5-4d40-8c9c-b2ed5fee3421/8f39f1d952423b0166ad?experience=power-bi))
- ✅ **Row-Level Security (RLS)** configured for Airline A
- ✅ **Scheduled refresh** set to 5:00 PM daily via default gateway

---

## 💡 Key Learnings

- End-to-end Power BI development cycle
- Data modeling, DAX, and real-time interactivity
- Publishing to Power BI Service with enterprise-level configuration

---

## 🛠️ Tools Used

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Power BI Service

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `dashboard.png` | Final dashboard screenshot |
| `Airline_Data_Analysis.pbix` | Power BI project file  |
| `Project_Report.pdf` | Project report document  |

---

## 🙋‍♂️ Author

**Aman Kumar Yadav**  
_BSc IT Graduate | Data Analyst Aspirant_  
[LinkedIn Profile](https://www.linkedin.com/in/aman-yadav-6b64b6253/)

---

## 📬 Contact

If you'd like to collaborate, provide feedback, or discuss job opportunities:

📧 amanyadav32327@gmail.com 

📌 Location: India | Timezone: IST (UTC+5:30)

---

> 🔗 *Feel free to fork, share, or reuse this project as a Power BI case study!*
