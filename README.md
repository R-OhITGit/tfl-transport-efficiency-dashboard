# 🚇 TfL Transport Efficiency & Network Performance Analysis

An end-to-end data analytics project analyzing passenger journey volumes, seasonality, and station geography across the Transport for London (TfL) network using **MySQL Workbench** and **Tableau Public**.

---

## 📊 Live Interactive Dashboard

🔗 **[Click Here to View Live Tableau Dashboard](INSERT_YOUR_TABLEAU_PUBLIC_URL_HERE)**

![TfL Dashboard Preview](Tfl_Dashboard.png)

---

## 🛠️ Tech Stack & File Structure

* **Database & Data Pipeline:** MySQL Workbench, SQL (`.sql` scripts)
* **Data Sources:** Raw TfL period datasets and station GIS metadata (`.xlsx` / `.csv`)
* **Data Visualization:** Tableau Public

---

## 📌 Key Insights & Features

* **MySQL Data Pipeline:** Ingested raw TfL journey datasets and station GIS metadata. Created optimized SQL analytical views (`vw_tfl_journeys_by_mode`, `vw_tfl_annual_growth`) to transform wide period tables into time-series data structures.
* **Executive KPI Tiles:** High-level summary cards displaying total network volume, bus share, and tube share with official TfL brand styling.
* **Monthly Journey Trends:** Continuous line series tracking post-pandemic volume recovery and seasonal demand peaks.
* **Station GIS Map:** Interactive spatial plot mapping 470+ London transit stations by zone and network.
* **Annual Mode Breakdown:** Heatmap grid evaluating year-over-year passenger shifts across all modes.
