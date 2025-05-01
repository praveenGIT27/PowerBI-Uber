# 🚖 Uber Trip Analysis Dashboard (Power BI)

## 📌 Project Overview

This Power BI dashboard analyzes Uber trip data across various dimensions including time of day, day of week, trip type, payment method, vehicle performance, and more. It provides business stakeholders and analysts with an intuitive, interactive view of trip-level patterns and key metrics such as bookings, distance, and revenue.

The dashboard includes advanced Power BI features like:
- Dynamic Measure Toggle
- Drillthrough Navigation
- Slicers for Date and City
- Interactive Heatmaps
- Time-based Demand Analysis
- Bookmark Navigation

---

## 🗂 Dashboard Pages & Features

### 1️⃣ Overview Page
High-level summary with KPIs and breakdowns:
- Dynamic measure toggle (Total Bookings / Booking Value / Distance)
- KPI Tiles: Revenue, Avg Distance, Avg Time
- Visuals:
  - Donut charts by Payment Type and Trip Type
  - Area Chart by Pickup Date
  - Most Frequent Pickup & Dropoff
  - Longest Trip display
  - Vehicle Trip Analysis grid
  - Top Booking Locations

### 2️⃣ Time Analysis Page
Time-based demand exploration:
- Booking Frequency Area Chart (10-min interval)
- Line Chart (Day-wise booking trend)
- Heatmap by Hour vs Day
- Dynamic metric toggle support

### 3️⃣ Details Page (Drillthrough Enabled)
Trip-level breakdown with drillthrough functionality:
- Full trip record table (Pickup/Dropoff, Distance, Fare, Type)
- Dynamic filtering from Overview or Time Analysis
- “Back” button to return to source page

---

## 💡 How Stakeholders Can Use This Dashboard

### 🔁 Switch Metrics Instantly
Use the top toggle to switch between:
- `Total Bookings`
- `Total Booking Value`
- `Total Trip Distance`  
All visuals will respond dynamically without changing tabs.

### 🧭 Navigate Between Pages
Click:
- `Overview` for executive summary
- `Time Analysis` for hourly/daily demand trends
- `Details` for full data records  
Use the left-side navigation or back arrow after drillthrough.

### 🔍 Drillthrough to Details
Right-click any:
- Vehicle name
- Trip type
- Day in chart  
Select **Drillthrough → Details** to see filtered trip records.

### 📅 Filter by Date or City
Use the slicers at the top to limit analysis to specific:
- Dates (e.g. 01/06/2024 – 30/06/2024)
- City (if applicable)

### 🖱️ Hover Insights (if enabled)
Some charts support **tooltip-based drillthrough**. Hovering may display contextual mini-tables filtered by your selection.

---

## 📊 Key Metrics Tracked

- Total Bookings
- Total Booking Value ($)
- Total Trip Distance (miles)
- Average Revenue per Trip
- Average Trip Distance & Time

---


