# Flight Delay Analysis Project

**Author:** Sourav

## Tools & Technologies
- **SQL**: Data processing, KPI development
- **Tableau / Power BI**: Interactive dashboards, visualizations
- **Excel**: Data cleaning, reporting, visualizations

## Overview
This project analyzes **1.05 million flight records (2022)** to uncover and address operational inefficiencies in the U.S. aviation industry. Leveraging SQL, Excel, Tableau, and Power BI, the project extracts, transforms, and visualizes data to deliver actionable insights for reducing delays, optimizing schedules, and improving passenger satisfaction.

## Key KPIs Addressed
1. **Weekday vs. Weekend** flight statistics
2. **JetBlue Airways** cancellations on the first day of each month
3. **Week-wise, state-wise, and city-wise** flight delay statistics with airline details
4. Airlines with **no departure/arrival delay** for flights covering **2500–3000 miles**

## Technical Execution

### 1. Data Engineering with SQL
- Developed **13 KPIs** using advanced SQL queries (multi-table joins, conditional aggregations, time-based calculations)
- Found **73.51% (770.86K) flights on weekdays** and **26.49% (277.72K) on weekends**, linking weekend delays to higher passenger volume
- Calculated **JetBlue's first-day-of-month cancellations** (e.g., January: 13, February: 10)
- Resolved airport code inconsistencies and standardized airline names with **CASE statements**
- Created a **delay classification column** for accurate delay categorization

### 2. Geospatial and Temporal Analysis
- Mapped delay hotspots to states (**California, Alaska**) and cities (**Albany, Albuquerque**)
- Quantified **1.5 million delayed minutes on weekends**, attributing delays to peak travel and weather
- Identified **Southwest Airlines** with the highest total delay minutes (2.03M), and **United Airlines** with the most efficient long-haul flights (4.29K flights, 2500–3000 miles, minimal delays)

### 3. Interactive Dashboard Development
- Built dynamic dashboards in **Excel, Tableau, Power BI** with interactive filters (weekday, airline, state)
- Used heatmaps to visualize delay density in **Texas** and **Florida**
- Created bar charts ranking airlines by on-time performance (e.g., Delta vs. Frontier)
- Developed time-series visualizations for monthly cancellations, revealing **Q1 as JetBlue's most disrupted quarter**
- Generated Excel reports for quick data summaries

### 4. Advanced Analytics & Business Impact
- Identified **3.4K highly efficient long-haul flights** (2500–3000 miles, near-zero delays), suggesting optimal routing strategies
- Linked delays to specific airports (e.g., **Aberdeen, SD**) with infrastructure limitations, proposing targeted upgrades
- Recommended increased weekend staffing at major hubs and route optimization for long-haul flights
- Estimated **$2.1M annual cost savings** for JetBlue via proactive maintenance to reduce first-day-of-month cancellations

## Conclusion
This project demonstrates how **SQL, Excel, Tableau, and Power BI** can drive data-driven decision-making in aviation. The insights generated offer actionable recommendations to reduce delays, optimize schedules, and cut costs for airlines, ultimately enhancing