# 📊 Business Insights 360 – AtliQ Hardware  

## 🏬 Company Overview  
AtliQ Hardware (imaginary company) is a rapidly growing **electronics company** specializing in hardware products such as **PC accessories, printers, and more**.  

🌍 **Global Presence**: APAC, North America, Latin America, European Union  
🛒 **Sales Platforms**:  
- **Brick-and-Mortar Stores** → Croma, Best Buy  
- **E-Commerce** → Amazon, Flipkart  

🏬 **Sales Channels**:  
- **Retailers** – Third-party sellers  
- **Direct Stores** – AtliQ’s own outlets  
- **Distributors** – Used in restricted markets (e.g., China, South Korea)  

👉 Note: AtliQ’s customers are **retailers & distributors**, while the **end consumers** are users of its products.  

---

## 🔎 Problem Statement  
AtliQ Hardware relied heavily on scattered **Excel-based reporting**, which led to poor decision-making and heavy losses during expansion in Latin America.  
Competitors using **advanced analytics** gained an edge, leaving AtliQ struggling with outdated methods.  

To fix this, AtliQ launched a **data analytics initiative** to enable **data-driven, transparent, and faster decision-making**.  

---

## 🎯 Project Objective  
Build an **intuitive Power BI dashboard** that delivers **actionable insights** for:  
- Finance 📊  
- Sales 🛒  
- Marketing 📣  
- Supply Chain 🚚  
- Executive & Key Performers view 🏆  

This helps improve **transparency, accessibility, and efficiency** in decision-making.  

---

## 🛢 Data Overview  
The dataset consists of **two SQL databases** and **three Excel files**.  

### 📂 Excel Files  
- Operating Expenses  
- Targets (FY 2022 only)  
- Market Share (PC division only)  

### 🗄️ Databases  

**gdb041:**  
- Fact: `fact_forecast_monthly`, `fact_sales_monthly`  
- Dimension: `dim_customer`, `dim_market`, `dim_product`  

**gdb056:**  
- Tables: `freight_cost`, `gross_price`, `manufacturing_cost`, `post_invoice_deductions`, `pre_invoice_deductions`  

📅 **Timeframe**: Sep 1, 2017 → Dec 31, 2021 (AtliQ’s FY runs Sep–Aug)  

⚠️ **Note**: Dataset is part of a bootcamp project → cannot be shared.  

---

## 🧹 Data Cleaning & Transformation  
- **Standardized & Trimmed** → Removed spaces, fixed naming conventions  
- **Data Structuring** → Created `dim_date` for time-based analysis  
- **Table Merging** → Combined `fact_sales_monthly` + `fact_forecast_monthly` into `fact_actual_estimates`  
- **Derived Calculations** → Added pre-invoice deductions, cost metrics  
- **Optimization** → Disabled intermediate tables to reduce Power BI file size  

---

## 🛠 Tools Used  
- **Power Query** → Data cleaning & transformation  
- **Power BI** → Dashboard design & reporting  
- **DAX** → Calculations & KPIs  

---

## 💡 Key Insights  

### 📈 Business Growth & Finance  
- Net Sales growth: **~280% (FY19)** → **~350% (FY22)**  
- Net Profit % negative since 2020 due to **high ops & marketing costs**  

### 🌍 Revenue & Market Trends  
- **APAC** = largest market (India leading)  
- **LATAM** = weakest region  
- Amazon = top global customer every year  
- Nova (Austria) = smallest customer since FY20  
- Notebooks = highest revenue growth, but **negative Net Profit % (FY22)**  
- USB Flash Drives = underperforming in FY21–FY22  

### 🛒 Sales & Customers  
- Flat discounting model eroding margins → needs **performance-based discounts**  
- Some products (e.g., AQ 5000 Series Electron 9 5900X) had **zero sales in FY22**  

### 🚚 Forecast & Supply Chain  
- Forecast Accuracy: **86% (FY19)** → dropped to **73% (FY20, COVID impact)** → recovered to ~81% (FY22)  
- Inventory issues: **Excess in FY19–20**, **Shortages in FY21–22**  
- WFH surge (FY20) → stockouts in processors, keyboards, WiFi extenders  

### 🏆 Competitive & Market Share  
- PC market share: **~1% (FY21)** → **~6% (FY22)**  
- **India** fastest-growing market (~13% share in FY22)  
- **North America** = highest revenue but only **5% penetration**  

### 📊 Operational & Strategic  
- Peak sales: **Sep–Dec every year** (festive/holiday demand)  
- Retailers = **72% of revenue (FY22)**  
- UK & Germany = **high marketing costs, low ROI**  

---

## 📝 Recommendations  
✔️ Gradually reduce **ops & marketing costs** after securing market share  
✔️ Shift to **performance-based discounting** by product & customer  
✔️ Expand in **APAC (India focus)** for growth  
✔️ Reevaluate **Notebook pricing** → boost profitability  
✔️ Investigate **USB Flash Drive underperformance**  
✔️ Improve **forecast accuracy** with real-time data  
✔️ Develop **North America strategy** to increase market penetration  
✔️ Optimize **UK & Germany marketing spend**  
✔️ Align **inventory planning** with Sep–Dec demand surge  

---

## 🧠 Skills Gained  
- Business metrics interpretation → linking KPIs to company performance  
- Power BI dashboard design (user-centric, multi-domain)  
- Functional knowledge of **finance, sales, marketing, supply chain**  
- Storytelling with data for **executive-level reporting**  

---

## 📂 Repository Structure  
