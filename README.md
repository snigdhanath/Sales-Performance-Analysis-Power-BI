# Global Sales Performance & Trend Analysis Dashboard

## Project Overview
This Power BI dashboard provides a comprehensive look into global sales operations. By transforming raw transactional data into interactive visualizations, the report identifies key revenue drivers, regional performance, and seasonal sales trends.

## 🔗 Project Assets
* [Link to .pbix File](./Dashboard/Sales_Analysis.pbix)
* [Link to Dataset](./Data/Sales_Data.csv)

---

## 📊 Interactive Dashboard Preview

This dashboard is fully dynamic. Below are three different views demonstrating how the visual elements cross-filter based on regional selection.

### 1. Global Overview (No Filters)
*The default view showing total aggregated performance across all regions.*
<img width="1431" height="690" alt="Global Overview (Default)" src="https://github.com/user-attachments/assets/bee54eba-ffaa-45fd-9233-c757a48e6464" />


---

### 2. Regional Drill-Down: Germany vs. United States
*Comparing these two views highlights the dashboard's ability to recalculate KPIs, product rankings, and category distributions instantly.*

| **Germany View** | **United States View** |
| :--- | :--- |
<img width="1417" height="677" alt="Regional Insights (Germany)" src="https://github.com/user-attachments/assets/520c6dd6-f2ca-45ea-9db5-18e83f1729e9" />
 |<img width="1410" height="737" alt="Regional Insights (US)" src="https://github.com/user-attachments/assets/a2177614-4331-454a-b30f-9eec4c914caf" />
  |

> **Key Observation:** Notice that while **Laptops** are the top category globally, the **USA** market shows a much higher concentration in **Smartphones** (26.15%) compared to the global average, whereas **Germany** shows a very specific focus on high-end smartphone models.


## 🚀 Key Features & Insights
* **Executive KPIs:** Real-time tracking of Total Sales ($47K), Order Volume (39), and Customer Reach (11).
* **Product Mix Analysis:** Discovered that **Laptops** dominate the market share, accounting for **54.08%** of total revenue.
* **Geographic Insights:** Interactive filtering across USA, India, Germany, and China to compare regional market penetration.
* **Temporal Trends:** Leveraged Date Hierarchies to visualize sales fluctuations across Years, Quarters, and Months, identifying peak growth periods.

## 🛠️ Technical Skills Demonstrated
* **Data Cleaning & Transformation:** Utilized Power Query to resolve data type inconsistencies 
* **Data Modeling:** Implementation of automated date hierarchies for granular time-series analysis.
* **UI/UX Design:** Applied visual hierarchy principles to create an intuitive, user-friendly layout with cross-filtering capabilities.
* **Data Visualization:** Built a variety of charts (Donut, Bar, Line, and KPI Cards) to present multi-dimensional data clearly.

## 📁 Repository Structure
* **/Data**: Contains the raw CSV/Excel files used for the analysis.
* **/Dashboard**: Contains the `.pbix` Power BI project file.
* **/Screenshots**: High-resolution images of the dashboard for quick viewing.
* `README.md`: Project documentation (this file).

---

## 💡 How to Use
1. Download the `Sales_Analysis.pbix` file from the **/Dashboard** folder.
2. Open it using **Power BI Desktop**.
3. Use the slicers on the right to filter by **Country** or **Category** to see the dynamic updates across all visuals.
