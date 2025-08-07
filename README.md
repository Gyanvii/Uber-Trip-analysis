# 🚗 Uber Trip Analysis Dashboard (Power BI)

This Power BI project analyzes Uber trip data to uncover key business insights on booking trends, revenue generation, trip efficiency, time-based demand patterns, and operational performance. The dashboard is designed for data-driven decision-making by stakeholders in ride-sharing operations.

---

## 📊 Project Overview

The Uber Trip Analysis Dashboard includes **three comprehensive tabs**:

### 1️⃣ Overview Dashboard
- **KPIs Tracked**:
  - Total Bookings
  - Total Booking Value
  - Average Booking Value
  - Total Trip Distance
  - Average Trip Distance
  - Average Trip Time
- **Key Features**:
  - Dynamic measure selector (via disconnected table)
  - Visuals by Payment Type & Trip Type (Day/Night)
  - Vehicle Type analysis in a grid view with conditional formatting
  - Filters: Date, City, Vehicle Type
  - Dynamic chart titles and tooltips
  - Export to CSV/Excel option

### 2️⃣ Time Analysis Dashboard
- **Purpose**: Identify ride demand fluctuations across different times
- **Visuals Include**:
  - Pickup Time (10-min intervals) – Area Chart
  - Day-wise trends (Mon–Sun) – Line Chart
  - Hourly Heatmap (Hour vs Day) – Matrix Visual
- **Global Dynamic Measure**: All visuals are controlled by a unified KPI selector

### 3️⃣ Details Tab
- **Functionality**:
  - Drill-through from other dashboards
  - Grid table showing trip-level data
  - “View Full Data” bookmark for resetting filters
  - Key trip fields: Booking ID, Distance, Duration, Location, etc.

---

## 📍 Location Analysis Features
- Most Frequent Pickup & Drop-off Points
- Farthest Trip Distance (Outlier Analysis)
- Total Bookings by Top 5 Locations
- Most Preferred Vehicle Type per Pickup Location

---

## 🛠️ Enhancements & UX Features
- **Dynamic Measure Titles**
- **Clear Filter Button** – One-click reset
- **Data Bookmarks** – Popups for metric explanations
- **Download Raw Data** – CSV/Excel export using Power BI or Power Automate

---

## 📁 File Contents
- `Uber_Trip_Analysis.pbix` – Power BI Desktop file with all dashboards
- `screenshots/` – Visual previews of the dashboards
- `README.md` – Project documentation

---

## ✅ Expected Outcomes
- Detect booking and revenue trends over time
- Analyze trip duration and distance efficiency
- Identify peak demand periods and top locations
- Support strategic decisions on pricing, driver allocation, and customer experience

---

## 📦 Tools & Technologies
- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query Editor
- Power BI Service (for publishing & sharing)

---

## 🔒 Disclaimer
This dashboard is for educational and demo purposes. It does not use real Uber data. All visualizations and KPIs are based on sample data to simulate real-world analytics scenarios.

---


