# 🚦 Road Traffic Analytics Dashboard

## 📌 Project Overview

The Road Traffic Analytics Dashboard is an end-to-end Data Engineering and Business Intelligence project designed to analyze road traffic patterns, vehicle distribution, EV adoption trends, and regional traffic insights. The project leverages Microsoft Fabric, PySpark, SQL, and Power BI to transform raw traffic data into actionable business insights.

---

## 🎯 Business Objective

The primary objective of this project is to help transportation authorities and planners:

- Identify high-traffic regions
- Monitor EV adoption trends
- Analyze peak traffic hours
- Compare traffic volumes across years
- Understand road category utilization
- Visualize geographic traffic hotspots
- Support infrastructure planning and decision-making

---

## 🛠️ Technology Stack

- Microsoft Fabric
- OneLake
- Lakehouse
- PySpark
- SQL
- Delta Tables
- Power BI
- DAX

---

## 🏗️ Architecture

Raw CSV Files
↓
Bronze Layer (Raw Data)
↓
Silver Layer (Data Cleaning & Transformation)
↓
Gold Layer (Business Aggregations)
↓
Power BI Dashboard

---

## 📂 Data Engineering Pipeline

### Bronze Layer
- Ingested multiple traffic and road CSV files into OneLake.
- Stored raw datasets without modifications.

### Silver Layer
- Removed duplicate records.
- Handled null values.
- Standardized column names.
- Converted data types.
- Created derived columns such as Total Traffic and Total EV Vehicles.

### Gold Layer
Created business-ready tables for:
- Regional Traffic Analysis
- EV Adoption Analysis
- Traffic Trend Analysis
- Peak Hour Analysis
- Road Demand vs Supply Analysis
- Traffic Density Analysis

---

## 📊 Power BI Dashboard

### KPI Cards
- Total Traffic
- Total EV Vehicles
- Total Non-EV Vehicles
### Dashboard Visualizations

#### 1. Regional Traffic Analysis
- Clustered Column Chart
- Total Traffic by Region

#### 2. Peak Hour Analysis
- Area Chart
- Total Traffic by Hour

#### 3. Traffic Trend Analysis
- Line Chart
- Total Traffic by Year

#### 4. EV Adoption Analysis
- Clustered Column Chart
- EV vs Non-EV Vehicles by Region

#### 5. Vehicle Distribution
- Donut Chart
- EV vs Non-EV Vehicle Share

#### 6. Road Category Analysis
- Matrix Visual
- Total Traffic by Road Category

#### 7. Geographic Analysis
- Map Visual
- Latitude
- Longitude
- Region Name
- Total Traffic
######
<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/f80c738f-73c7-4036-beaa-a0c724498c9f" />

