# 📈 E-Commerce Performance Growth Analysis

## 📊 Project Overview

This project was developed as part of my work at **Daraz** to analyze **GMV (Gross Merchandise Value)** and **Order trends** across multiple categories and time periods.  
The main goal was to build a unified SQL framework that measures **business growth performance** across industries on a **monthly, quarterly, and yearly** basis — enabling strategic visibility into key trends and seasonality.

---

## 🧩 Problem Statement

E-commerce platforms handle vast amounts of transactional data across multiple product categories, time periods, and markets.  
However, measuring true **growth performance** across such dimensions can be complex due to:
- Fragmented datasets and inconsistent time windows  
- Different seasonal baselines and comparison periods  
- A need for consistent, automated reporting across all key categories  

This project aimed to:
- Automate GMV and Orders growth tracking across timeframes  
- Build category-level comparability using a standardized SQL logic  
- Provide a consistent and scalable growth analysis template for business teams  

Due to confidentiality, raw data and exact performance figures are not included.

---

## 🧠 Approach

- Designed and implemented a **comprehensive SQL script** using **ODPS SQL** to calculate:
  - **Last Month (LM)**, **Current Month (CM)**, **Current Quarter (CQ)**, and **Current Year (CY)** performance.  
  - Corresponding **growth rates** compared to last year’s same periods (LLM, LCM, LCQ, LY).  
- Categorized product data into major **industries** (e.g., Electronics, Fashion, Lifestyle, FMCG, Digital Goods).  
- Applied conditional aggregation and time window logic using `ADD_MONTHS`, `datetrunc`, and `INTERVAL` functions.  
- Ensured clean data inputs by excluding irrelevant accounts, low-value items, and incomplete fulfillments.  
- Computed final outputs with percentage growths for **GMV** and **Orders** at industry level.

---

## 📊 Metrics Calculated

| Metric Type | Description |
|--------------|--------------|
| **GMV (Gross Merchandise Value)** | Total sales value for each industry over defined time periods |
| **Orders** | Number of fulfilled transactions per industry |
| **Growth Rates** | Month-over-Month, Quarter-over-Quarter, and Year-over-Year % growth for both GMV and Orders |
| **Industry Segmentation** | Grouped by product category for high-level strategic analysis |

---

## 🛠️ Tools & Technologies

- **SQL (ODPS / Alibaba MaxCompute)** – for aggregation logic and data computation  
- **Excel / Power BI** – for output visualization and reporting (optional)  
- **Databricks / Python (optional)** – for downstream analysis and automation  

---

## 📈 Outcome / Impact

- Delivered an **automated and scalable SQL script** to track performance growth across multiple time dimensions.  
- Enabled **cross-category performance comparisons** for leadership decision-making.  
- Reduced manual reporting effort by fully automating GMV and Orders growth computation.  
- Provided a **foundation for visualization dashboards** used in strategic planning.

---

## 🔒 Confidentiality Note

Due to company data protection policies, datasets and exact performance results are not disclosed.  
This repository focuses on the **SQL logic, methodology, and analytical structure** used for growth tracking.

---

## 👤 Author

**Noor Wali**  
Growth & Data Analyst | Daraz  
[LinkedIn](https://www.linkedin.com/in/your-link) | [GitHub](https://github.com/noorw8354)

---

### 🔖 Tags
#SQL #EcommerceAnalytics #GMV #GrowthAnalysis #Daraz #BusinessIntelligence  
#DataAnalytics #PerformanceTracking #Automation #DataEngineering
