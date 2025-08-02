# 📦 NZ Retail Inventory Optimization & Forecasting Dashboard

## 🧩 Overview

This project addresses a critical challenge in New Zealand’s retail sector: **working capital strain caused by excess inventory due to misaligned supply and demand**. By leveraging **forecasting models**, integrating **multiple datasets**, and developing a **professional Power BI dashboard**, this solution empowers decision-makers to optimize inventory and uncover potential cost savings.

---

## 🔍 Problem Statement

New Zealand retailers often hold surplus inventory, tying up significant working capital. This issue is driven by inaccurate demand predictions and delayed supply alignment. The need was clear: **a data-driven approach to identify inventory inefficiencies and enable proactive decision-making**.

---

## ✅ Objectives

* Forecast future sales using historical data.
* Identify gaps between **forecasted demand** and **actual inventory**.
* Provide actionable insights for supply chain and finance teams.

---

## ⚙️ Solution Approach

### 🧠 Forecasting & Data Modeling

* Developed a **time series forecasting model** using **Facebook Prophet** in Python.
* Forecasts were generated at a regional and industry level (Retail & Accommodation sectors).
* Integrated outputs with historical retail sales, inventory levels, cost data, and capacity constraints.

* ## Retail Chain Analysis

A full retail analytics project focused on sales forecasting, regional trends, and supply chain optimization using Python and real New Zealand retail data.

[[Open In Google Colab](https://colab.research.google.com/drive/1HNeipCXFOV6OaLeO5Z4xd4KLEWg9W5DY?usp=sharing)]


### 📊 Python-Based Analytical Pipeline

* Built a forecasting-driven inventory optimization model using Python, combining time series predictions with business metrics.

* Prophet Forecasting: Used Facebook Prophet to forecast inventory demand at a quarterly level for all regions.

* Forecast Accuracy Metrics: Computed MAE, RMSE, and MAPE to evaluate model performance.

* Sales-Proportional Inventory Allocation: Allocated forecasted inventory by region based on regional sales share.

* Inventory Efficiency Metrics: Calculated Excess Inventory, Holding Costs, and Forecast Error at region level.

* Top 10 Region Matrix: Created a clean KPI matrix highlighting regions with highest excess stock.

* Visualizations with Plotly: Generated interactive heatmaps, bar charts, and KPI tables to visualize inventory inefficiencies.

---

## 🛠 Tech Stack

| Tool                  | Purpose                               |
| --------------------- | ------------------------------------- |
| **Python (Prophet)**  | Sales forecasting (Time Series)       |
| **Pandas & NumPy**    | Data cleaning and transformation      |
| **Stats NZ Datasets** | Official historical data sources      |

---

## 📈 Results & Impact

* Delivered a data-rich, decision-ready analytics solution that:

* Uncovered critical inefficiencies in inventory allocation, highlighting regions and quarters with excess stock and missed demand signals.

* Quantified cost-saving potential through measurable reductions in holding costs and excess inventory, enabling proactive budget realignment.

* Empowered cross-functional teams with clear, visual diagnostics—supporting agile responses to forecast mismatches and regional disparities.

* Strengthened data-driven strategic planning by linking supply chain decisions to working capital optimization, financial health, and operational resilience.

---

## 📂 Project Structure

```
NZ-Retail-Inventory-Optimization/
│
├── data/
│   ├── Annual_Enterprise_Survey_2023.csv
│   ├── CPI.csv
│   ├── Forecast.csv
│   ├── Forecast_Model.csv
│   ├── Inventory.csv
│   ├── Regional_Sales.csv
│   ├── Retail_Sales.csv
│   ├── Retail_Trade_Sales_and_stocks_by_industry_1995–2025.csv
│   ├── Wholesale.csv
│   └── nz_retail_inventory_optimized.csv
│
├── forecasting/
│   └── supply_chain_forecasting.ipynb
│
├── powerbi/
│   ├── NZ_Inventory_Optimization.pbix
│   └── pbix_visual_map.md          
│
├── visuals/
│   ├── dashboard_screenshots/
│   │   ├── regional_heatmap.png
│   │   ├── top10_excess_bar.png
│   │   └── executive_summary_table.png
│   └── final_presentation_figures/
│
├── documentation/
│   ├── README.md
│   ├── insights_summary.md
│   └── markdown_tables.md          
│
├── reports/
│   └── NZ_Retail_Case_Report.pdf
│
└── requirements.txt                
```
