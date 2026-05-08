# Global Sales Performance & Trend Analysis Dashboard

## Project Overview
This Power BI dashboard provides a comprehensive look into global sales operations. By transforming raw transactional data into interactive visualizations, the report identifies key revenue drivers, regional performance, and seasonal sales trends.

## 🔗 Project Assets
* **Power BI File:** [Download Dashboard](./Dashboard/First_PowerBI_Dashboard.pbix)
* **Raw Data:** [Orders Dataset](./Data/orders.csv) | [Customers Dataset](./Data/customers.csv)

---


## 📊 Interactive Dashboard Preview

This dashboard is fully dynamic. Below are three different views demonstrating how the visual elements cross-filter based on regional selection.

### 1. Global Overview (Default)
*The aggregated view of all sales data across all regions for 2026.*
![Global View](./Screenshots/Main_Dashboard.jpg)

---

### 2. Regional Comparison: Germany vs. USA
*Selecting a country from the slicer instantly recalculates the KPI cards, product rankings, and category distributions.*

| **Germany View** | **United States View** |
| :--- | :--- |
| ![Germany View](./Screenshots/Germany_Dashboard.jpg) | ![US View](./Screenshots/US_Dashboard.jpg) |

---
 



## 🚀 Key Insights
* **Revenue Leader:** **Laptops** are the primary revenue driver, accounting for over **54%** of total sales globally.
* **Top Product:** The **Dell XPS 15** is the highest-selling individual item by volume.
* **Regional Growth:** The **United States** represents the largest market share in this dataset with **$23K** in total sales.
* **Temporal Trends:** Sales peaked significantly in **November 2026**, suggesting strong seasonal demand or successful marketing campaigns.

## 🛠️ Technical Skills Demonstrated
* **Data Transformation:** Cleaned and converted text-based date strings into functional **Date Hierarchies**.
* **Dynamic Modeling:** Built interactive slicers for geographic and category-based drill-downs.
* **Visual Storytelling:** Designed a balanced layout using KPI cards, time-series line charts, and part-to-whole donut charts.
* **GitHub Documentation:** Organized project assets into a structured repository for professional transparency.

---

## 📁 Repository Structure
* **/Data**: Raw CSV files (`orders.csv`, `customers.csv`).
* **/Dashboard**: The functional Power BI file (`First_PowerBI_Dashboard.pbix`).
* **/Screenshots**: Image gallery showing the dashboard in various filtered states.
