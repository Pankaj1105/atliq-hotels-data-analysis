
## 📄 Business Requirement Document (BRD)

### 📌 Project: Data Analysis for Athletic Grants – Hospitality Domain

---

### 🧭 Business Overview

**AtliQ Grands** is a well-established hotel chain operating in major Indian cities: **Delhi**, **Mumbai**, **Bangalore**, and **Hyderabad**. It offers a diverse portfolio of hotel types:

- **Luxury Hotels** (e.g., *Athletic Bay Palace*)
- **Business Hotels** (e.g., *Athletic Seasons*)

The hotel chain features multiple **room categories**, such as:

- Standard
- Deluxe
- Premium
- Residential

**Room bookings** can occur through the following channels:

- 🏨 *Athletic Grants official website*
- 🌐 *Third-party platforms* like MakeMyTrip, Goibibo, and Tripster

All bookings and transactions are stored in a **centralized mission-critical OLTP database**.

---

### 💼 Business Problem

Despite a strong market presence, **Athletic Grants is losing revenue and market share**. Rising competition has prompted the leadership to shift toward **data-informed decision-making**.

The management wants answers to key business questions, such as:

- 🏙️ Which cities or hotel types are underperforming?
- 🛏️ What are the occupancy rates across regions and room categories?
- ❌ How do cancellations impact revenue?
- 💳 Which booking channels deliver the best or worst ROI?

---

### 🎯 Project Objective

The goal of this project is to conduct **Exploratory Data Analysis (EDA)** to identify patterns, anomalies, and business insights using booking data from the company’s data warehouse.

The analysis will be performed in **Python** using **Jupyter Notebook**, based on **CSV files exported via ETL** from the data warehouse.

---

### ⚙️ System Constraints & Technical Considerations

- The **OLTP (transactional) system** cannot be directly queried due to its performance-critical nature.
- An **ETL (Extract, Transform, Load)** pipeline replicates data into a **data warehouse (OLAP system)**.
- For this project, CSV files simulate the ETL output from the data warehouse.
- The data analysis will be isolated from the live system to prevent performance degradation.

---

### 🛠️ Tools & Technologies

| Component         | Technology                |
|------------------|---------------------------|
| Language          | Python                    |
| Environment       | Jupyter Notebook          |
| Libraries         | pandas, NumPy, (optional) Matplotlib, Seaborn |
| Data Format       | CSV (Data Warehouse Export) |

---

### 📈 Project Scope

The project will follow these steps:

1. **Understand business goals** and define analytical questions
2. **Load and explore CSV data** (5+ dimensional and fact tables)
3. **Clean and transform** data (handle nulls, outliers, incorrect values)
4. Perform **EDA** to identify trends, patterns, and anomalies
5. **Generate insights** and data visualizations to answer business questions
6. *(Optional)* Provide actionable business recommendations

---

### 📊 Expected Deliverables

- ✅ Cleaned, structured datasets ready for analysis
- ✅ Insightful analytics on:
  - City-wise performance
  - Room category and hotel type utilization
  - Booking platform effectiveness
  - Cancellation trends and revenue impact
- ✅ Visualizations to support findings
- ✅ *(Optional)* Summary report/dashboard for stakeholders

---

### 🧱 Key Concepts Used

- **OLTP (Online Transaction Processing)**: Handles real-time bookings and financial transactions
- **OLAP (Online Analytical Processing)**: Supports large-scale analysis and decision-making
- **ETL (Extract, Transform, Load)**: Pipeline used to move and prepare data from OLTP → OLAP

---

### 🧾 Summary

This project simulates a real-world data analysis workflow in the **hospitality industry**. It is designed for **aspiring Data Analysts or Data Scientists** and demonstrates how to:

- Analyze multi-source booking data
- Extract actionable insights
- Help business teams at Athletic Grants make informed, data-backed decisions






---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧾 Resume Project Summary

### 📌 Project Title: AtliQ Hotels Data Analysis

**Tools & Technologies**: `Python`, `Pandas`, `Jupyter Notebook`, `Data Cleaning`, `Exploratory Data Analysis (EDA)`, `Data Transformation`, `Matplotlib`  

---

### 📄 Description:
This project simulates a real-world business scenario for **AtliQ Hotels**, a fictional hotel chain operating in **Delhi, Mumbai, Bangalore, and Hyderabad**, that is facing declining revenue and occupancy. As part of a data-driven initiative, this project focuses on analyzing their booking and revenue datasets exported from a simulated data warehouse.

---

### ✅ Key Responsibilities & Accomplishments:

- Performed **end-to-end data analysis** on 5+ CSV datasets including bookings, hotel metadata, room details, and aggregated KPIs.
- Cleaned messy data, handled outliers, null values, and data inconsistencies using pandas.
- Conducted **exploratory data analysis (EDA)** to uncover trends in:
  - **Occupancy rates by city, room category, and day type (weekday/weekend)**
  - **Revenue realized per city and month**
  - **Booking platform performance**
- Engineered new metrics such as **occupancy percentage** and merged dimension/fact tables for enriched analysis.
- Delivered **actionable insights** to support revenue optimization and operational decision-making.

---

### 🧠 Key Business Insights Derived:

- **Mumbai** led in both occupancy and revenue, while **Hyderabad** consistently underperformed.
- **Weekend bookings** saw higher occupancy, revealing potential to optimize weekday pricing.
- **Standard rooms** had the highest demand; **premium/luxury rooms** showed underutilization.
- Monthly revenue trends showed seasonality—peaks in **March and May**, a dip in **June**.

---

### 💼 Outcome:
This project demonstrates a complete data analytics workflow aligned with industry practices—covering **data cleaning**, **transformation**, and **insight generation**—making it suitable for inclusion in a professional resume or data portfolio.
