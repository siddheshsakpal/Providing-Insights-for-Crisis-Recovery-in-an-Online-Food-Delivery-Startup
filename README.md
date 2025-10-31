# 🍔 QuickBite Express — Crisis Analysis & Recovery Dashboard (Jan–Sep 2025)

🎥 **Project Presentation (YouTube):** [https://youtu.be/KNShc5xcLeA?si=LICe89a8vb52J9KX](https://youtu.be/KNShc5xcLeA?si=LICe89a8vb52J9KX)  
📊 **Interactive Power BI Dashboard:** [https://app.powerbi.com/view?r=eyJrIjoiY2FjYjg5NDQtZjQ5MS00MDc0LWE5MzgtOTZmMmMyNDAxYjMwIiwidCI6IjYzMGE3YWY1LTVmYWUtNDVkZC04MDVlLTdjN2IyNDk4YWZjNSJ9](https://app.powerbi.com/view?r=eyJrIjoiY2FjYjg5NDQtZjQ5MS00MDc0LWE5MzgtOTZmMmMyNDAxYjMwIiwidCI6IjYzMGE3YWY1LTVmYWUtNDVkZC04MDVlLTdjN2IyNDk4YWZjNSJ9)

---

## 🧭 Project Overview

**QuickBite Express** is a Bengaluru-based food-tech startup founded in 2020 that connects customers with nearby restaurants and cloud kitchens.  

In **June 2025**, QuickBite faced a major **crisis** due to:  
- Food safety violations at partner restaurants.  
- A week-long delivery outage during monsoon season.  
- Competitor campaigns from Zomato & Swiggy that exploited the situation.  

The incident caused a severe drop in orders, revenue, and customer trust.

---

## ❓ Problem Statement

QuickBite management requested a data-driven investigation to understand:

- Which customer segments can be re-engaged?  
- How did demand, revenue, and ratings shift across phases (pre-crisis vs crisis)?  
- What was the impact on delivery performance and cancellations?  
- Which recovery levers (discounts, audits, partnerships) are most effective?  
- How did sentiment and feedback trends evolve during the crisis?

---

## 🧩 Data Model & Duration

- **Period:** January 2025 → September 2025  
  - Pre-Crisis: Jan–May 2025  
  - Crisis: Jun–Sep 2025  

### Tables Used:
**Fact Tables:** `fact_orders`, `fact_order_items`, `fact_ratings`, `fact_delivery_performance`  
**Dimension Tables:** `dim_customer`, `dim_restaurant`, `dim_delivery_partner`, `dim_menu_item`

---

## 💼 Tasks (Role: Business Analyst - Peter Pandey)

1. Perform **data cleaning & transformation** in Power BI / Power Query.  
2. Derive KPIs: Orders, Revenue, AOV, Rating, Cancellation Rate, SLA, DTV.  
3. Compare metrics across **pre-crisis vs crisis periods**.  
4. Conduct **sentiment analysis** on review text and visualize keywords.  
5. Design a **Recovery Dashboard** with actionable metrics.  
6. Present findings and recommendations via Power BI and YouTube presentation.  

---

## 📈 Primary Analysis

| Focus Area | Description / Metric | Key Findings |
|-------------|----------------------|---------------|
| **Monthly Orders Trend** | Orders (Jan–Sep 2025) | ~70% drop in June; slow recovery by September. |
| **City-Wise Decline** | Top 5 impacted cities | Bengaluru (70.23%), Mumbai (70.18%), Ahmedabad (69.89%), Pune (69.81%), Kolkata (69.79%). |
| **Restaurant Performance** | Top 10 restaurants with ≥50 pre-crisis orders | Largest declines among high-volume partners. |
| **Cancellation Rate** | % of cancelled orders | Jumped from 3% → 18% in June. |
| **Delivery SLA (DTV)** | Actual vs Expected delivery time | Average deviation ↑ by 25%. |
| **Customer Ratings** | Avg rating per month | Dropped from 4.6 → 3.4 in June. |
| **Sentiment Analysis** | Word cloud of reviews | Frequent negatives: *Late*, *Cold*, *Refund*, *Hygiene*. |
| **Revenue Impact** | (Pre − Crisis) / Pre × 100 | Revenue fell ~68%. |
| **Loyalty Impact** | Loyal users churn | 35% of loyal users churned; 30% had avg rating > 4.5. |

---

## 🔍 Secondary Analysis

| Topic | Insight |
|-------|----------|
| **Competitor Benchmark** | Swiggy & Zomato drop < 40%, QuickBite ≈ 68%. |
| **CAC Surge** | Ads cost tripled; ROI on paid channels fell sharply. |
| **Recovery Levers** | Food safety audits, cashbacks, trusted partnerships. |
| **Behavior Shift** | Customers moved from premium to low-value “survival” meals. |
| **Priority Cities** | Tier-1 cities (Bengaluru, Mumbai) show long-term demand risk. |
| **Feedback Trends** | Negative reviews spike aligned with outage week. |

---

## 💡 Key Insights

- **Orders ↓ ~70%** & **Revenue ↓ ~68%** due to crisis.  
- **Customer satisfaction** plunged sharply (avg rating ↓ from 4.6 to 3.4).  
- **SLA deviation ↑ 25%**, causing higher cancellation rates.  
- **Loyal customer churn = 35%**, mainly high-value users.  
- **Top negative keywords:** “Late”, “Cold”, “Refund”, “Hygiene”.  
- **CAC tripled** during crisis; retention cost exceeded acquisition gain.  

---

## 🛠️ Recommendations

**Short-Term (0–3 months):**  
- Delivery & hygiene audits; refund transparency.  
- Cashback for loyal and lapsed customers.  

**Medium-Term (3–9 months):**  
- Partner retraining; enforce SLA penalties.  
- Brand rebuild campaign using verified food safety messaging.  

**Long-Term (9–18 months):**  
- Introduce loyalty tiers and gamification.  
- AI-driven real-time delivery monitoring and sentiment tracking.  

---

## 📂 Deliverables

- 🎥 **Presentation Video:** [YouTube Project Walkthrough](https://youtu.be/KNShc5xcLeA?si=LICe89a8vb52J9KX)  
- 📊 **Power BI Dashboard:** [Interactive Report Link](https://app.powerbi.com/view?r=eyJrIjoiY2FjYjg5NDQtZjQ5MS00MDc0LWE5MzgtOTZmMmMyNDAxYjMwIiwidCI6IjYzMGE3YWY1LTVmYWUtNDVkZC04MDVlLTdjN2IyNDk4YWZjNSJ9)  
- 📄 **Presentation Deck:** *QuickBite Express Crisis Analysis.pptx*  
- 🧮 **Data Model:** `fact_orders`, `fact_order_items`, `fact_ratings`, `fact_delivery_performance`  
- 🗂️ **Dimensions:** `dim_customer`, `dim_restaurant`, `dim_menu_item`, `dim_delivery_partner`  

---

## 👨‍💼 Author

**Siddhesh Sakpal**  
Business Analyst | Power BI Developer | Data Storyteller  
📧 siddheshsakpal03@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/siddhesh-sakpal-34625b157)

---

*This repository is part of the Codebasics Resume Challenge.  
All data used is simulated for learning and visualization purposes.*
