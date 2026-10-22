# 📊 E-Commerce Retail & Consumer Behavior Analysis (Excel & Tableau)
## 🌐 Live Interactive Deployments
* **🔗 Live Tableau Interactive Dashboard:** [View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/kira.barrios/viz/E-CommerceConsumerBehaviorRetailAnalyticsDashboard/Dashboard1?publish=yes)


## 📌 Project Overview
## 📌 Project Overview
This project evaluates online sales performance, transaction logistics, and customer demographic satisfaction for an e-commerce platform. Using a raw dataset of online purchases, I engineered a multi-stage analytics pipeline across two distinct environments: building a centralized, spreadsheet-driven visual grid in **Microsoft Excel** and scaling those operational metrics into an interactive, cloud-hosted **Tableau Public** dashboard. 

By analyzing these datasets side-by-side, I uncovered critical purchasing behaviors, tracked core key performance indicators (KPIs), and delivered data-driven business recommendations aimed at maximizing platform profitability and consumer retention.


---

## 🛠️ Tech Stack & Features Used
* **Business Intelligence Tools:** Microsoft Excel (Desktop App for Mac) & Tableau Public (Cloud Hosting)
* **Excel Capabilities:** Advanced Pivot Tables, Value Field Aggregations, Data Visualizations (Clustered Column Charts), Custom Data Grouping, and Multi-Table Interactive Slicers.
* **Tableau Capabilities:** Calculated Fields (`Total Revenue` multiplication metrics), Custom Bins/Generational Grouping, Dual-Axis Aggregations (AOV Trend Lines vs. Transaction Volume), and Interactive Cross-Filtering Dashboard Engine.


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
* **Analysis:** Segmented customers into distinct generational brackets (`18-27`, `28-37`, `38-47`, `48-57`, `58+`) and calculated the average review score for each group to isolate variances in user satisfaction.
* **Finding:** Customer satisfaction remained universally stable, maintaining a steady overall platform average rating of 4.0 out of 5 across all age groups.
* **Recommendation:** Maintain the current website layout and user interface design since it proves universally accessible across generations, shifting UX engineering resources instead toward site speed or order fulfillment features.

### 4. High-Value Customer Profiles: Which demographic spends the most?
* **Analysis:** Cross-references customer age brackets against the average revenue generated per transaction to locate the highest-value consumer base.
* **Finding:** The 48–57 age bracket emerged as the highest-spending consumer demographic, yielding the peak Average Order Value (AOV) on the platform.
* **Recommendation:** Allocate digital advertising budgets specifically toward the 48–57 age demographic, tailoring marketing campaigns around premium product bundles to maximize return on ad spend (ROAS).

---

## 🎛️ Interactive Dashboard Interfaces

### Microsoft Excel (Local Deployment)
Features a centralized business analytics grid driven by a dynamic **Gender Slicer**. I engineered cross-report table connections, allowing stakeholders to isolate product performance, transactional logistics, consumer satisfaction, and high-value spending metrics simultaneously by targeted customer gender.

### Tableau Public (Cloud Deployment)
Features an advanced **2x2 Cross-Filtering Dashboard Engine**. Instead of relying on floating menu boxes, I activated comprehensive action filters on all four core worksheets. Selecting any specific data block—such as the Electronics bar or the 48-57 generational tier—instantly triggers real-time visual animations and cross-report recalibrations across the entire layout.
 

---

## ⚠️ Data Limitations & Demographics
* **Unlabeled Demographic Records:** The raw dataset contained transaction records with an unassigned string in the gender category, which appeared as `(blank)` inside the Pivot Table environment.
* **Portfolio Adjustments:** To ensure a clean executive user interface, these unlabeled rows were filtered out of the visual slicer display. However, all records remain fully intact within the underlying `DATA` sheet to preserve total revenue and transaction calculations without bias.

---

## 📁 How to View the Project

### Option 1: Live Cloud Deployment
1. Scroll to the top of this page and click the **Live Tableau Interactive Dashboard** hyperlink under the deployments section.
2. Interact with the live visualizations, charts, and cross-report funnel filters directly inside your web browser.

### Option 2: Local Excel Desktop App
1. Download the `Ecommerce_sales_analysis.xlsx` file from this repository workspace.
2. Open the file natively inside desktop Microsoft Excel to access the centralized analytics grid and dynamic Gender Slicers.

