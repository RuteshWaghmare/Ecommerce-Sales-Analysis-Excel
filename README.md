# 📊 Vrinda Store Annual Data Analysis 2022

![Excel](https://img.shields.io/badge/Tool-Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Category-Data_Analysis-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Project Overview
This project provides an end-to-end data analysis of **Vrinda Store's 2022 annual sales**. The primary objective of this project is to analyze a dataset of over **31,000 online orders** to extract meaningful insights about customer behavior, channel performance, and regional sales trends. 

The resulting interactive dashboard enables stakeholders to make data-driven decisions to optimize marketing spend, manage inventory, and maximize revenue for 2023.

---

## 🎯 Business Questions Answered
The analysis was designed to answer the following 5 critical business questions:
1. **Revenue Seasonality:** What is the overall sales trend across the year, and which months generate the most revenue?
2. **Customer Demographics:** Which specific customer demographic (Gender & Age Group) drives the highest lifetime value and sales volume?
3. **Channel Efficiency:** Which e-commerce platforms (Amazon, Flipkart, etc.) dominate our sales distribution?
4. **Geographical Targeting:** What is the geographical distribution of our sales, and which Top 3 states warrant the highest localized marketing budgets?
5. **Operational Health:** What is our current order fulfillment rate, and what proportion of revenue is lost to returns or cancellations?

---

## 📈 Executive Summary & Real Insights
*(Data extracted from `Vrinda Store Data Analysis Report.xlsx`)*

* **Total Revenue:** ₹2,11,76,377 (~₹2.11 Cr)
* **Total Orders Processed:** 31,047

### 1. Demographic Highlights
* **Women dominate purchasing:** Women accounted for **₹1.35 Crore** in sales, compared to men (₹76.1 Lakhs).
* **Target Age Group:** The **Adult segment (approx. 30-49 years)** is the most lucrative. Specifically, *Adult Women* alone account for **~57.2%** of all orders across the year.

### 2. Channel Performance
* **The "Big Three" Platforms:** E-commerce sales are heavily concentrated in three platforms which drive **~80.5%** of total order volume:
  * **Amazon:** 35.5% 
  * **Myntra:** 23.4%
  * **Flipkart:** 21.6%

### 3. Geographical Distribution
The top 3 revenue-generating states are:
1. **Maharashtra:** ₹29.9 Lakhs
2. **Karnataka:** ₹26.4 Lakhs
3. **Uttar Pradesh:** ₹21.0 Lakhs

### 4. Seasonality & Operations
* **Peak Sales Month:** **March** was the highest performing month, generating **₹19.28 Lakhs** from 2,819 orders. 
* **Order Fulfillment:** The business maintains a strong operational health with a **92.2% delivery success rate** (28,641 successfully delivered orders out of 31,047), with returns sitting at just ~3.3%.

---

## 💡 Strategic Recommendations for 2023
Based on the data insights, the following actions are recommended to the business stakeholders:

1. **Precision Marketing:** Reallocate ad spend to heavily target **Women in the Adult age bracket** residing in **Maharashtra, Karnataka, and Uttar Pradesh**.
2. **Channel Optimization:** Negotiate better margin rates or invest heavily in sponsored ads on **Amazon and Myntra**, as they are the undisputed primary sales drivers.
3. **Seasonal Inventory Planning:** Prepare maximum inventory and logistics capacity for the **Q1 peak (January - March)** to capitalize on the highest consumer buying trends.

---

## 🖼️ Interactive Dashboard
*(The dashboard features dynamic slicing by Month, Channel, and Category.)*

![Dashboard Snapshot]([link-to-your-uploaded-Snapshot-of-Vrinda-Store-Annual-Report.jpg](https://github.com/RuteshWaghmare/Ecommerce-Sales-Analysis-Excel/blob/main/Snapshot%20of%20Vrinda%20Store%20Annual%20Report.jpg?raw=true))

---

## 🛠️ Data Processing & ETL
1. **Data Cleaning:** Addressed missing values, standardized formatting, and corrected data types for dates and monetary values.
2. **Data Processing:** Created new calculated columns (e.g., Age Buckets: Teen, Adult, Senior) and extracted the `Month` from the `Order Date` for time-series analysis.
3. **Data Visualization:** Utilized advanced Pivot Tables and Pivot Charts to build an interactive, user-friendly dashboard.

---

## 📁 Repository Structure
```text
├── Data/
│   ├── raw_dataset.csv             # Original unprocessed data
│   ├── processed_data.csv          # Cleaned dataset ready for analysis
├── Visuals/
│   ├── Snapshot_of_Dashboard.jpg   # High-res export of the dashboard
├── Vrinda_Store_Annual_Report.xlsx # Final working Excel file with Pivot tables
└── README.md                       # Project documentation
