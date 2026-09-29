# 📊 Sales Insights & Performance Analytics Dashboard (2024 - 2025)

## 📌 Executive Summary
The **Sales Insights Dashboard** is a comprehensive, multi-page Business Intelligence solution built in **Power BI**. It provides decision-makers with actionable insights into corporate sales performance, product profitability, customer demographics, fulfillment metrics, and sales representative targets for the period of **2024 - 2025**.

---

## 📐 Architecture & Page Breakdown

The dashboard is structured into 4 interactive pages accessible via a centralized navigation panel:

1. **Landing Page:** Main gateway with quick navigation buttons to all report sections.
2. **Executive Overview:** High-level summary of financial KPIs, sales trajectories, category breakdowns, and branch distribution.
3. **Products & Customers Analysis:** Detailed evaluation of inventory demand, top-revenue products, customer segments, and return rates.
4. **Branches & Team Performance:** Operational review of branch goals, sales rep benchmarks, cancellation rates, delivery metrics, and payment channels.

---

## 📑 Detailed Page Analysis & Data Breakdown

### 1️⃣ Executive Overview Page
Focuses on strategic executive metrics and overall business health.
<img width="1085" height="621" alt="image" src="https://github.com/user-attachments/assets/1a82513a-e3a0-477e-ab66-7d282c8e33dc" />


* **Key Performance Indicators (KPIs):**
  * **Net Sales:** `$28M` (Total revenue earned after discounts/returns)
  * **Profit:** `$4M` (Net profit earned)
  * **Profit Margin:** `15.36%` (Overall operational profitability ratio)
  * **Orders:** `1.61K` (Total orders placed)
  * **Avg Orders Value:** `$17.68K` (Average revenue per order)

* **Visualizations Breakdown:**
  * **Monthly Net Sales (This Year vs Last Year) [Line Chart]:** Tracks sales velocity across months, highlighting peak performance in April (`$2.88M`) and November (`$3.16M`).
  * **Sales By Category [Donut Chart]:**
    * **Mobiles:** `38.49%` (Primary revenue driver)
    * **Laptops:** `33.47%`
    * **Home Appliances:** `15.23%`
    * **TV & Audio:** `10.64%`
    * **Accessories:** `2.16%`
  * **Sales By Branch [Bar Chart]:** Compares performance across branches (e.g., Smouha Branch leading ahead of Mansoura and Nasr City).
  * **Branch Map:** Geospatial mapping of branch locations and regional revenue concentrations.

---

### 2️⃣ Products & Customers Page
Analyzes product catalog demand, inventory performance, and customer purchasing behaviors.
<img width="1191" height="675" alt="image" src="https://github.com/user-attachments/assets/dd55dcbe-8b57-46c3-94ac-7d26cfc79209" />


* **Key Performance Indicators (KPIs):**
  * **Units Sold:** `5.92K` total units shipped.
  * **Unique Customers:** `1.6K` active buyers.
  * **Return Rate:** `6.36%` product return percentage.
  * **Avg Selling Price:** `$13.02K` per unit sold.

* **Visualizations Breakdown:**
  * **Top 10 Products [Horizontal Bar Chart]:**
    1. **Samsung Galaxy S24:** `$5.5M`
    2. **iPhone 15 128GB:** `$4.9M`
    3. **iPad 10th Gen 64GB:** `$4.7M`
    4. **Apple MacBook Air:** `$3.7M`
    5. **HP 15 Core i5:** `$3.6M`
    *(Followed by Asus Vivobook, Oppo Reno 11, Lenovo ThinkPad, Samsung A35, and Xiaomi Redmi Note).*
  * **Category Performance [Clustered Bar Chart]:** Displays Net Sales vs. Profit Margin across main product lines.
  * **Customer Segments [Donut Chart]:**
    * **Individual:** `69.31%`
    * **Small Business:** `20.19%`
    * **Corporate:** `10.5%`
  * **Sub_Category Breakdown [Treemap]:** Visual representation of sub-category volumes under Mobiles, Laptops, Home Appliances, and TV & Audio.
  * **Top 5 Customers [Data Table]:** Lists top revenue-generating customers (Mariam Tawfik: `$1.47M`, Hossam Mansour: `$698K`, Aya Mansour: `$638K`, Aya Fouad: `$634K`, Jihan Ezzat: `$629K`).

---

### 3️⃣ Branches & Team Page
<img width="1185" height="677" alt="image" src="https://github.com/user-attachments/assets/0f161b49-462e-46b2-852f-824bbdc2c213" />


Monitors sales representative performance, operational target tracking, and order fulfillment metrics.

* **Key Performance Indicators (KPIs):**
  * **Target Achievement:** `95.07%` overall target completion rate.
  * **Sales vs Target Gap:** `-$4.00M` shortfall against set quotas.
  * **Cancellation Rate:** `6.96%` order cancellation percentage.
  * **Avg Delivery Days:** `1.34 days` average fulfillment cycle.

* **Visualizations Breakdown:**
  * **Actual vs Target | Monthly [Combo Bar & Line Chart]:** Tracks monthly actual net sales against target thresholds, showing strong performance in November & December.
  * **Target Achievement [Gauge Chart]:** Visual gauge displaying target progress toward the `$81M` target goal (currently at `$77M`).
  * **Top Sales Representatives [Bar Chart]:** Ranks sales reps by individual sales contributions (Tarek Attia leading, followed by Khaled Seif, Wael Soliman, and others).
  * **Payment Method [Donut Chart]:**
    * **Cash:** `34.74%`
    * **Credit Card:** `28.36%`
    * **Installment:** `20.02%`
    * **Mobile Wallet:** `16.87%`
  * **Customer & Order Status [Stacked Column Chart]:** Breaks down order outcomes across In-Store, Online, and Phone order channels.

---

## 🛠️ Technical Stack & Implementation

* **Data Cleaning & Transformation:** Handled using **Power Query** (null handling, data type standardization, custom column creations).
* **Data Modeling:** Extended Star Schema establishing relationships between Sales Fact Tables and Dimension Tables (Date, Customers, Products, Branches, Sales Reps).
* **DAX Calculations:** Written for Time Intelligence measures (YTD, Prior Year comparisons), dynamic profit margins, target attainment ratios, and conditional KPI indicators.
* **UI/UX Design:** Modern dark theme styling with clear hierarchy, contrasting card backgrounds, consistent margins, and responsive filter slicers (Region, Month, Year).

---

## 💡 Key Business Takeaways

1. **Revenue Drivers:** Mobile devices and laptops account for **over 70%** of total business revenue, driven primarily by flagship smartphones like Samsung S24 and iPhone 15.
2. **Customer Base:** Retail / Individual buyers dominate sales, suggesting marketing budgets should stay heavily focused on B2C channels while creating growth strategies for B2B Corporate clients.
3. **Fulfillment Efficiency:** Delivery time is exceptionally fast at **1.34 days**, contributing to low cancellation rates (**6.96%**).
