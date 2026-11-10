# 📈 Marketing Campaign Performance & A/B Testing Analysis

## 🎯 Project Overview
This project focuses on an advanced exploratory data analysis (EDA) and statistical evaluation of a retail marketing campaign dataset (`WA_Marketing-Campaign.csv`). Beyond traditional high-level reporting, this analysis digs deep into **business intelligence, statistical hypothesis testing (ANOVA), and behavioral insights** to optimize ad spend and maximize return on investment (ROI).

---

## 🔍 Key Business Questions Addressed
Instead of just asking which campaign performed best, this project answers high-impact strategic questions:
1. **Ad Fatigue Analysis:** Do campaigns lose effectiveness over time, or do sales remain stable across consecutive weeks?
2. **Store Maturity Synergy:** Do newly established stores (`AgeOfStore`) respond differently to promotions compared to mature, long-standing stores?
3. **Market Size Efficiency:** Which promotions yield the highest efficiency across different market scales (Small, Medium, Large) to prevent budget waste?
4. **Consistency & Risk Analysis:** Which campaign offers the most stable and reliable sales performance rather than just high volatility peaks?

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Analysis:** `pandas`, `numpy`
* **Statistical Testing:** `scipy.stats`, `statsmodels` (ANOVA & hypothesis testing)
* **Data Visualization:** `matplotlib`, `seaborn`

---

## 📊 Key Findings & Insights
* **Promotion 1 Dominance:** Achieved the highest average sales overall ($\approx 58.1k$) with high stability and a balanced coefficient of variation.
* **Statistical Significance (ANOVA):** The variance between campaign performances was proven statistically significant ($p$-value $< 10^{-9}$), confirming the results are not due to random chance.
* **Store Maturity Impact:** New stores showed exceptional responsiveness to aggressive campaigns (Promotions 1 and 3), generating top-tier sales, while underperforming campaigns failed entirely in new markets.
* **Ad Fatigue Resilience:** Time-series analysis across the 4-week span proved that top campaigns maintained stable momentum without major audience burnout.

---

## 📁 Repository Structure
```text
marketing-campaign-analysis/
│
├── data/
│   └── WA_Marketing-Campaign.csv          # Raw dataset
│
├── notebooks/
│   └── Marketing_Campaign_Analysis.ipynb  # Jupyter Notebook containing full python code
│
├── outputs/
│   └── figures/                           # Generated charts & plots
│       ├── ad_fatigue_trend.png
│       └── sales_by_market_size.png
│
├── README.md                              # Project Documentation
└── requirements.txt                       # Required python packages