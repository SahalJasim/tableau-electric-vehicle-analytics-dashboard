# tableau-electric-vehicle-analytics-dashboard
Interactive Tableau dashboard analyzing 3,000 EV records across 10 brands and 4 global regions. Covers performance metrics, battery health, cost of ownership, CO₂ savings, and resale depreciation.

# ⚡ Electric Vehicle Performance & Cost Intelligence

![Dashboard Preview](dashboard_screenshot.png)

## 📌 Project Overview
An interactive Tableau dashboard analyzing electric vehicle performance, 
cost of ownership, battery health, and carbon impact across 4 global 
regions and 10 major brands.

Built as part of the Techolas Technologies Data Analytics Program.

---

## 📂 Dataset
- **Source:** Kaggle — Electric Vehicle Analytics Dataset
- **Records:** 3,000 vehicles
- **Fields:** 25 features
- **Regions:** Asia, Australia, Europe, North America
- **Brands:** Tesla, BMW, Ford, Hyundai, Audi, Mercedes, 
             Volkswagen, Chevrolet, Nissan, Kia

---

## 🔧 Tools Used
- **Tableau Desktop** — Dashboard & Visualization
- **Python / Excel** — Data exploration & validation

---

## 🧹 Data Cleaning Steps
1. Checked for null values — none found across all 3,000 rows
2. Verified no duplicate records
3. Corrected data types (Year → Whole Number, costs → Decimal)
4. Renamed columns for readability
5. Flagged outliers — 6 zero-temperature rows, high charging costs retained
6. Created 4 calculated fields (Vehicle Age, Total Annual Cost, 
   Charging Efficiency, Range Band)

---

## 📊 Dashboard Features

### KPI Cards
| Metric | Value |
|--------|-------|
| Total Vehicles | 3,000 |
| Avg Battery Health | 85% |
| Avg CO₂ Saved | 15.03 tons |
| Avg Annual Cost | $7,625 |

### Charts
- **Registrations by Brand** — Horizontal bar chart
- **Avg Range by Vehicle Type** — Grouped bar chart
- **Monthly Charging Cost Trend** — Line chart (2015–2024)
- **CO₂ Saved by Region** — Treemap
- **Resale Value Depreciation** — Area chart by vehicle age

### Filters / Slicers
- Region (Single select)
- Vehicle Type (Multi-select checkbox)

---

## 💡 Key Insights
1. Ford leads brand registrations but no single brand dominates the market
2. Sedans average the longest range at 382.6 km across all regions
3. Australia contributes the highest CO₂ savings at 11,818 tonnes
4. Resale value drops steepest between age 0–3 then flattens — 
   best time to buy used is age 4+
5. Average annual ownership cost of $7,625 covers charging, 
   maintenance, and insurance

---

## ✅ Recommendations
- Fleet buyers should diversify across brands — no dominant EV maker yet
- Sedans are optimal for range-critical operations
- Purchase used EVs at age 4+ for best value retention
- Australia's EV adoption model worth studying for other regions

---
