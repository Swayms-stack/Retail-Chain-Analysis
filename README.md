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
* Build an **interactive Power BI dashboard** to:

  * Visualize forecast vs actual performance.
  * Reveal excess or insufficient inventory across time periods.
  * Simulate inventory and cost-saving scenarios.
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


### 📊 Dashboard Development

* Created a **rich, multi-page Power BI dashboard** with the following features:

  * **Forecast vs Actual Sales Comparison** by region, industry, and quarter.
  * **Inventory Efficiency Metrics**: Days of Inventory on Hand, Holding Costs, Over/Under Stock ratios.
  * **DAX-driven KPIs** highlighting financial impact and performance gaps.
  * **Scenario Analysis**: What-if simulations to model savings under optimized inventory levels.
  * **Decomposition Trees** and **Drill-through Pages** for deeper diagnostic insights.

---

## 🛠 Tech Stack

| Tool                  | Purpose                               |
| --------------------- | ------------------------------------- |
| **Python (Prophet)**  | Sales forecasting (Time Series)       |
| **Pandas & NumPy**    | Data cleaning and transformation      |
| **Power BI**          | Dashboard development & visualization |
| **DAX**               | Calculated KPIs and scenario logic    |
| **Stats NZ Datasets** | Official historical data sources      |

---

## 📈 Results & Impact

* Developed a **professionally designed dashboard** that reveals:

  * Hidden inefficiencies in inventory holdings.
  * Significant cost savings opportunities through optimized supply alignment.
  * Enables **data-driven decisions** that improve **working capital management**, reduce waste, and enhance supply chain agility.

---

## 📂 Project Structure

```
NZ-Retail-Inventory-Optimization/
│
├── data/
│   ├── AES_2023.csv
│   ├── Retail_Trade_Sales_by_Region_2011Q2–2025Q1.csv
│   └── Forecast_Model_Prophet_Output.csv
│
├── forecasting/
│   └── prophet_model.ipynb
│
├── powerbi/
│   └── NZ_Inventory_Optimization.pbix
│
├── visuals/
│   └── dashboard_screenshots/
│
├── README.md
└── requirements.txt
```
