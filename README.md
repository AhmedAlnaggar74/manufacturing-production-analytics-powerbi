# 🏭 Manufacturing Production & Operational Efficiency Analytics

## 📌 Executive Summary
This project delivers a comprehensive Power BI dashboard analyzing 1,000 hybrid manufacturing operational records. The analytical focus centers on **Equipment Effectiveness**, **Machine Availability**, **Energy Consumption**, and **Task Completion/Failure Rates** across critical operations (Lathe, Grinding, Milling, Additive, and Drilling).

---

## 📊 Key Operational Metrics (KPIs)
- **Total Jobs Processed:** 1,000 Jobs
- **Machine Availability:** 89.16%
- **Total Energy Consumption:** 8.52K kWh
- **Job Completion Rate:** 67.30%
- **Job Failure Rate:** 12.90%

---

## 🛠️ Data Pipeline & Architecture
1. **Data Cleaning & Transformation (Power Query):**
   - Handled missing (`null`) values for unstarted/failed job schedules.
   - Preserved operational nuances such as negative start delays (early setup starts).
   - Standardized data types across date-time, duration, and metrics fields.
2. **Data Modeling & DAX:**
   - Established a Star Schema with a custom DAX Date Table (`Dim_Date`).
   - Built DAX measures for dynamic failure/completion rate calculations and aggregation filters.
3. **UI/UX Design:**
   - Designed a structured layout using executive container styling, high-contrast visual hierarchy, and precise data labeling.

---

## 💡 Key Business Insights
1. **Operational Bottlenecks:** Lathe and Grinding operations record the highest total job volume, requiring targeted preventive maintenance to minimize failure risks.
2. **Energy Efficiency:** Energy usage directly correlates with processing times; optimizing machine setup idle time reduces overall kWh consumption.
3. **Capacity Management:** Machine processing times show uniform distribution (~13K–15.5K mins per machine), indicating balanced workload assignment across workstations.

---

## 🛠️ Tools & Technologies Used
- **Power BI Desktop** (DAX, Power Query, Data Modeling, Data Visualization)
- **Microsoft Excel / CSV Data Pipelines**

 ---

 ## 🛡️ License

This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm Ahmed Alnaggar. I'm a data analyst.
