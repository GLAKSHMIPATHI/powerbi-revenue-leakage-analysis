# 📊 Revenue, Marketing ROI & Leakage Analysis (Power BI)

## 📌 Business Problem
Organizations often see revenue growth but struggle to understand **what is real growth vs price-driven**, whether **marketing spend is efficient**, and **where revenue leaks operationally**.

This project builds an **executive-grade Power BI dashboard** to analyze:
- True revenue performance
- Pricing vs volume-driven growth
- Marketing ROI by platform & channel
- Revenue leakage from discounts and returns
- Operational inefficiencies hidden behind topline numbers

---

## ❓ Key Business Questions Answered
- How much revenue did we *actually* make?
- How much growth came from **price increases vs volume**?
- Which marketing platforms deliver the **best ROI**?
- Where is revenue leaking — **discounts or returns**?
- Which **categories, platforms, and channels** are risk-heavy?

---

## 🧠 Executive Summary
- **Net Revenue peaked in Jul’23 (₹3.22L)**, contributing ~23% of annual revenue.
- Early growth was **volume-led**, while **H2 growth became price-driven**.
- The **largest divergence between Net and Adjusted Revenue occurred in Nov’23**, indicating pricing impact rather than demand growth.
- **Marketing ROI varies significantly by platform**, highlighting efficiency gaps.
- **Returns contribute more to leakage than discounts**, pointing to post-purchase operational issues.
- Leakage % remains **stable (0.21–0.26)**, suggesting persistent process inefficiencies rather than isolated issues.

---

## 🗂️ Dashboard Pages

### 1️⃣ Executive Summary
High-level KPIs and narrative insights for leadership decision-making.

<img width="1145" height="630" alt="Screenshot 2025-12-24 171055" src="https://github.com/user-attachments/assets/109bc478-18dc-403c-a4ed-4c0efe0d0229" />


---

### 2️⃣ KPI & Trends
Core revenue, pricing, and growth KPIs with time-based trends.

<img width="1139" height="655" alt="Screenshot 2025-12-24 170600" src="https://github.com/user-attachments/assets/4deb6878-e4d3-42da-a9d4-72f58c7904d0" />


**Includes**
- Net Revenue
- Adjusted Revenue (After Price Changes)
- Price Impact
- Daily Ad Spend
- Marketing ROI
- MoM Revenue Growth %

---

### 3️⃣ Trends & Drivers
Explains *why* performance changed — efficiency vs volume vs pricing.

<img width="1153" height="653" alt="Screenshot 2025-12-24 170655" src="https://github.com/user-attachments/assets/564eb381-69fd-4f56-bfed-cbc76d99eb69" />


**Includes**
- Ad Spend vs Net Revenue
- Operational Loss Trend
- Revenue Leakage Breakdown
- Leakage Source Comparison

---

### 4️⃣ Leakage by Category / Platform
Deep-dive into where revenue is being lost operationally.

<img width="1148" height="647" alt="Screenshot 2025-12-24 170741" src="https://github.com/user-attachments/assets/ce09c46e-8e29-4022-beca-277eb23767e3" />


**Insights**
- Returns are the dominant leakage driver
- Certain category–channel combinations are high risk
- Leakage is structurally consistent across months

---

### 5️⃣ Platform → Channel Drill-through
Interactive drill-through to trace performance from platform to channel.

<img width="413" height="309" alt="Screenshot 2025-12-24 170850" src="https://github.com/user-attachments/assets/fdc360f6-a20f-489e-85ac-ab1ee791e8a0" />

**Purpose**
- Identify which platforms drive revenue into which channels
- Compare ROI, revenue, and leakage together
- Support targeted budget reallocation

---

## 🧱 Data Model Overview
- **Fact Table**
  - Sales_Fact (Revenue, Quantity, Discounts, Returns)
- **Dimension Tables**
  - Calendar
  - Products
  - Web_Product_Map
  - Ads_Campaigns
  - Price_Changes
- **Model Design**
  - Star schema
  - Explicit DAX measures only
  - Logical measure folders:
    - Revenue
    - Volume
    - Pricing
    - Leakage
    - Growth
    - Marketing

---

## 📐 Key Metrics Defined
- **Net Revenue** – Actual realized revenue
- **Adjusted Revenue** – Revenue after cumulative price changes
- **Price Impact** – Revenue driven purely by pricing
- **True Growth** – Volume-driven growth
- **Marketing ROI** – Revenue per unit of ad spend
- **Leakage %** – Operational revenue loss ratio

---

## 🛠️ Tools & Techniques Used
- Power BI Desktop
- DAX (MoM, cumulative pricing, ROI, leakage metrics)
- Star schema data modeling
- Custom tooltips for attribution clarity
- Drill-through design for deep analysis
- Executive narrative storytelling


---

## ✅ Outcome
Delivered an **executive-ready Power BI dashboard** that clearly explains:

> **What happened → Why it happened → Where action is required**

This project demonstrates **business-focused analytics**, not just visualization.

---

## 👤 Author
**G Lakshmi Pathi**  
Aspiring Data Analyst  
