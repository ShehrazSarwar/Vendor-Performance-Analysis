# Vendor Performance & Strategic Analytics

## 📌 Project Overview

This project is an end-to-end analytical ecosystem designed to optimize procurement and vendor management. By processing **1.8 GB of retail data**, the project transitions from raw CSV ingestion to **Statistical Hypothesis Testing**, answering critical business questions regarding capital efficiency, vendor dependency, and pricing optimization.

## 🚀 Key Analytical Objectives

The project was engineered to solve the following business challenges:

### **1. Strategic Growth & Pricing**

* **Growth Opportunity:** Identified **"High Margin, Low Volume"** brands to unlock potential through targeted marketing and pricing adjustments.
* **Bulk Purchase Optimization:** Conducted price-sensitivity analysis to determine if bulk purchasing reduces unit price and identified the **optimal purchase volume** for maximum cost savings.

### **2. Vendor & Brand Performance**

* **Sales Leadership:** Benchmarked Vendors and Brands to identify top-tier sales performers.
* **Procurement Dependency:** Analyzed the concentration of total purchase dollars to determine the business's **dependency risk** on top-tier vendors.

### **3. Inventory & Capital Efficiency**

* **Slow-Moving Stock:** Identified vendors with **low inventory turnover**, highlighting inefficiencies and slow-moving products.
* **Capital Analysis:** Calculated the exact **capital locked in unsold inventory** per vendor to prioritize stock liquidation strategies.

### **4. Statistical Validation & Hypothesis Testing**

To ensure data-driven decision-making, the project includes rigorous statistical validation:

* **Confidence Intervals:** Calculated **95% Confidence Intervals** for profit margins of both top and low-performing vendors.
* **Hypothesis Testing (A/B Testing Logic):**
* **Null Hypothesis ($H_0$):** No significant difference exists in mean profit margins between vendor tiers.
* **Alternative Hypothesis ($H_a$):** Mean profit margins are significantly different, justifying a tiered vendor management strategy.



## 🛠️ Tech Stack & Methodology

* **Data Ingestion:** Automated **Python (SQLAlchemy)** pipeline for **1.8 GB** datasets.
* **SQL EDA:** Complex **T-SQL CTEs** for multi-million row aggregations and KPI calculations.
* **Python EDA & Statistics:** Used **Pandas and Scipy** for EDA, Hypothesis Testing (T-Tests) and Confidence Intervals.
* **Visualization:** **Power BI** for executive-level dashboards and **Matplotlib/Seaborn** for statistical distribution plots.

---

*This repository demonstrates a fusion of Data Engineering scale with the analytical depth of a Data Scientist.*
