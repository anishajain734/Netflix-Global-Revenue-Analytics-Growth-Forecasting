# 🎬 Netflix Strategic Financials: Predictive Revenue & Regional Analysis

## 📌 Project Overview
This Power BI dashboard provides a comprehensive analysis of Netflix’s global financial performance.

Moving beyond historical reporting, this project integrates **predictive forecasting** to project revenue trends and correlates subscriber growth with financial health across four major global regions: **UCAN, EMEA, APAC, and LATAM**.

**Key Objective:**  
To provide a single source of truth for executive decision-makers to monitor churn, regional market share, and future revenue trajectories.

---

## 🚀 Executive Features

- **Predictive Revenue Forecasting**  
  Built-in AI forecasting used to project global revenue trends into 2026, including confidence intervals (cone of uncertainty).

- **Correlation Analytics**  
  Interactive visuals showing the relationship between membership growth and revenue scaling.

- **Global KPI Command Center**  
  Real-time visibility into:
  - Global Revenue: **$149.56bn**
  - Regional Revenue Split
  - Churn Rate: **-0.30**

- **Premium Thematic Design**  
  High-contrast Netflix-style UI optimized for executive readability and impact.

---

## 🛠️ Technical Deep-Dive

### 1. Data Architecture (Snowflake Schema)
The data model is built on a **Snowflake Schema** to ensure financial accuracy and scalability.

It normalizes multiple datasets including:
- Income & Loss statements  
- Regional revenue breakdowns  
- Subscription tiers and membership data  

---

### 2. Advanced DAX & Analytics

- **Churn Rate Logic**  
  Custom DAX measures to compute negative churn as a growth indicator.

- **Regional Market Share**  
  Dynamic comparisons between UCAN dominance and emerging APAC/LATAM markets.

- **Time Intelligence**  
  Year-over-Year (YoY) and Quarter-over-Quarter (QoQ) financial performance tracking.
