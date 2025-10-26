# Agricultural Productivity Analysis (Power BI Dashboard)

## Project Overview

This project analyzes the intricate relationship between **historical rainfall patterns** and **agricultural crop yields** across various Indian states from 1966 to 2017. The goal is to provide data-driven insights to stakeholders on climate-related risks, water management priorities, and regional efficiency.

---

## Dashboard Key Features

The interactive Power BI dashboard provides a comprehensive view of the analysis:

* **Temporal Trend Analysis:** Line charts comparing annual **Total Rainfall** against **Average Yield** to identify high-risk (drought) years.
* **Geographic Variation:** Maps highlighting regional disparities in yield efficiency (Yield per mm of rain).
* **Critical Month Correlation:** Visualizations proving that **excessive July and August rainfall** negatively impacts productivity in key monsoon states.
* **Interactivity:** Slicers for **State, Year,** and **Crop Type** enable deep-dive analysis.

---

## Technologies Used

* **Data Analysis and Visualization:** Power BI
* **Data Source:** `rain-agriculture.csv` (Historical Indian agricultural and rainfall data)
* **Modeling:** Power Query (Data Cleaning, Unpivoting), DAX (Measures for Total Rainfall, Average Yield)
---

## Lessons Learned & Skills Gained

This project provided hands-on experience in the end-to-end data analytics workflow, from raw data preparation to strategic recommendation.

### Technical Skills Gained:
* **Data Transformation (Power Query):** Mastered data cleaning techniques, including identifying and removing duplicate columns, checking for missing values, and the crucial technique of **Unpivoting** to transform a wide dataset into a long format suitable for robust time-series and comparative analysis.
* **Data Modeling & DAX:** Developed key analytical measures using DAX (e.g., `Total Rainfall`, `Average Yield`) and established essential relationships, enabling complex calculations beyond simple aggregation.
* **Advanced Visualization:** Utilized **Combo Charts (Line and Clustered Column)** with secondary axes to effectively compare metrics with vastly different scales (rainfall in mm vs. yield in Kg/ha), a critical technique for displaying correlation.
* **Geographic Analysis:** Used Power BI maps to visualize regional performance metrics like Yield Efficiency, identifying geographic outliers.
