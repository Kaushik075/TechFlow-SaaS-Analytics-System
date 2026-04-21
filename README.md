# TechFlow-SaaS-Analytics-System
An end-to-end SaaS analytics system built to simulate how product, growth, and revenue teams analyze user behavior, identify churn risks, and drive data-backed decisions.

## 📌 Problem Statement

SaaS companies operate on fragmented data across subscriptions, payments, and product usage.

This creates key blind spots:
- Where is revenue leaking?
- Which users are at risk of churn?
- Which products drive the most value?
- What behaviors correlate with retention vs churn?

---

## 🧠 System Overview

This project builds a **relational analytics system** that answers these questions using SQL-driven analysis.

<img width="991" height="652" alt="Image" src="https://github.com/user-attachments/assets/86be8faa-ec26-4e92-b9c6-bd8f6d3870a8" />

### Data Model (6 Core Tables)
- `users`
- `subscriptions`
- `payments`
- `products`
- `subscription_items`
- `user_activity`

The system enables:
- Customer lifecycle tracking
- Revenue analysis
- Churn detection
- Product adoption insights

---

## ⚙️ Tech Stack

- **MySQL** – Data modeling & analysis  
- **Python** – Synthetic data generation  
- **SQL (Advanced)** – CTEs, Window Functions, Aggregations  
- **GitHub** – Version control & documentation  

---

## 📊 Core Analyses

### 1. Customer Lifetime Value (CLV)
- Identified top revenue-generating users  
- Example: Highest lifetime spenders exceed **$20,000+**

---

### 2. Revenue Trends (MoM)
- Subscription growth peaked at **+207.28% (May 2025)**
- Decline observed: **-13.48% (Aug 2025)**  
→ Indicates volatility in acquisition/retention

---

### 3. Churn Analysis
- Churn increased from:
  - **814 (Apr 2025)** → **4575 (Aug 2025)**  
→ ~5.6x increase in churn

- Low activity + payment failures → highest churn probability

---

<img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/080fcaf0-2d6d-40c9-84e6-ff5aade3c0be" />

---

### 4. RFM Segmentation (Behavioral Segments)
- Segmented users into:
  - Champions
  - Loyal
  - At Risk
  - Lost
  - New

→ Identified **high-value but at-risk users** for retention targeting

---

### 5. Product Bundling Insights
Top co-purchased combinations:
- CustomerTool Management + ProjectTool Form → **569**
- CustomerTool Late + ProjectTool Bring → **568**
- DataViz Analytics + ProjectTool Cell → **568**

→ Clear cross-sell & bundling opportunities

---

### 6. Payment Performance
- All methods ~85% success rate
- Slight variation:
  - PayPal: **85.01%**
  - Credit Card: **84.91%**

→ Payment method is **not the main churn driver**

---

### 7. Plan-Level Revenue Insights
| Plan | Subscriptions | Revenue |
|------|-------------|--------|
| Enterprise | 59,986 | $52.88M |
| Pro | 60,310 | $13.27M |
| Basic | 59,759 | $2.29M |
| Free | 59,915 | $0 |

→ Revenue is heavily skewed toward **Enterprise tier**

---

## 📈 Key Insights

- Churn is rising significantly despite user growth  
- Revenue concentration is high in enterprise customers  
- Product bundling shows strong cross-sell patterns  
- Payment success is stable → churn driven by behavior, not transactions  
- Growth is inconsistent → requires retention-focused strategy  

---

## 🧩 Business Impact

This system enables:

- Targeted retention strategies for at-risk users  
- Pricing & bundling optimization  
- Identification of high-value customer segments  
- Revenue forecasting and growth diagnostics  

---

## 🔮 Future Scope

- Churn prediction model (Logistic Regression / Survival Analysis)  
- Real-time dashboard (Power BI / Streamlit)  
- Cohort-based retention tracking  
- Experimentation (A/B testing framework)  

---




## ▶️ How to Run

1. Run SQL schema:

DATA BASE CREATION.sql


2. Generate data:

python generate_techflow_sub_data.py


3. Run analysis queries:

BUSINESS PROBLEMS - SOLUTIONS.sql


---

## 👤 Author

**Kaushik Yeddanapudi**  
- Aspiring Product / Growth Analyst  
- Focus: SaaS Analytics, Funnel Analysis, Revenue Systems  

---

