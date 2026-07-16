# 📊 E-Commerce Retail & Consumer Behavior Analysis (Excel)

## 📌 Project Overview
This project evaluates online sales performance, transaction logistics, and customer demographic satisfaction for an e-commerce platform. Using a dataset of online purchases, I built an interactive executive dashboard in Microsoft Excel to uncover purchasing patterns, track key performance indicators (KPIs), and deliver data-driven business recommendations aimed at maximizing platform profitability and consumer retention.

---

## 🛠️ Tech Stack & Features Used
* **Tool:** Microsoft Excel (Desktop App for Mac)
* **Features:** Advanced Pivot Tables, Value Field Aggregations, Data Visualizations (Clustered Column Charts), Data Grouping, and Multi-Table Interactive Slicers.

---

## 🔍 Key Business Questions Answered

### 1. Product Performance: Which category drives the highest revenue?
* **Analysis:** Aggregated total revenue (Quantity × Price) across all product categories.
* **Finding:** Electronics emerged as the primary revenue engine for the platform.
* **Recommendation:** Optimize homepage real estate and seasonal promotional banners to prioritize high-margin electronic goods, ensuring inventory levels are scaled to meet consumer demand.

### 2. Payment Logistics: What is the preferred payment method and its impact?
* **Analysis:** Calculated the total transaction count per payment method alongside average order value (AOV) to evaluate checkout frequency against profitability.
* **Finding:** Cash on Delivery (COD) emerged as the most popular payment method by transaction volume, but Credit Card users generated the highest revenue, yielding the largest average basket size per checkout.
* **Recommendation:** Introduce targeted incentives, such as a 5% discount or loyalty points for cardholders, to encourage Cash on Delivery users to transition to digital credit payments, maximizing transaction profitability.

### 3. Demographic Satisfaction: Does user experience vary by age?
* **Analysis:** Utilized Excel's numeric grouping feature to segment customers into distinct generational brackets (`20-29`, `30-39`, etc.) and calculated the average review score for each.
* **Finding:** Customer satisfaction remained universally stable, maintaining a steady overall platform average rating of 4.0 out of 5 across all age groups.
* **Recommendation:** Maintain the current website layout and user interface design since it proves universally accessible across generations, shifting UX engineering resources instead toward site speed or order fulfillment features.

### 4. High-Value Customer Profiles: Which demographic spends the most?
* **Analysis:** Cross-references customer age brackets against the average revenue generated per transaction to locate the highest-value consumer base.
* **Finding:** The 48–57 age bracket emerged as the highest-spending consumer demographic, yielding the peak Average Order Value (AOV) on the platform.
* **Recommendation:** Allocate digital advertising budgets specifically toward the 48–57 age demographic, tailoring marketing campaigns around premium product bundles to maximize return on ad spend (ROAS).

---

## 🎛️ Interactive Dashboard Elements
The finalized spreadsheet features a centralized analytics grid. I integrated a dynamic **Gender Slicer** connected via cross-report connections, allowing stakeholders to filter product revenue, payment choices, consumer satisfaction, and high-value demographic spending profiles simultaneously by consumer gender. 

---

## ⚠️ Data Limitations & Demographics
* **Unlabeled Demographic Records:** The raw dataset contained transaction records with an unassigned string in the gender category, which appeared as `(blank)` inside the Pivot Table environment.
* **Portfolio Adjustments:** To ensure a clean executive user interface, these unlabeled rows were filtered out of the visual slicer display. However, all records remain fully intact within the underlying `DATA` sheet to preserve total revenue and transaction calculations without bias.

---

## 📂 How to View the Project
1. Download the `Ecommerce_sales_analysis.xlsx` file from this repository.
2. Open the file in desktop Microsoft Excel to interact with the slicers and live data charts.
