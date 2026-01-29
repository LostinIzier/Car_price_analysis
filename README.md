# 🚗 Used Car Price Analysis & Market Insights

## 📌 Project Overview
This project analyzes large-scale **used vehicle sales data** to extract **actionable business insights** related to pricing, depreciation, profitability, and regional demand.  
The analysis is designed from the perspective of **used-car dealers, marketplaces, and pricing teams**, focusing on how data can support **inventory planning, pricing strategy, and margin optimization**.

The project goes beyond basic EDA by benchmarking selling prices against **Manheim Market Report (MMR)** values, an industry-standard valuation metric used in the used-car market.

---

## 🎯 Business Objectives
The key goals of this analysis are to:

- Understand **how used-car prices evolve with vehicle age and mileage**
- Identify **brand-wise and state-wise demand and revenue patterns**
- Evaluate **pricing efficiency relative to market benchmarks (MMR)**
- Detect **high-risk and high-opportunity segments** in older vehicles
- Provide **data-backed insights** that can guide pricing and inventory decisions

---

## 📊 Dataset Description
- **Source:** Kaggle – Vehicle Sales Data  
- **Records:** 500K+ used vehicle sales  
- **Key Features:**
  - Vehicle details: make, model, body type, transmission
  - Usage metrics: odometer, vehicle age
  - Pricing: selling price, MMR (market valuation)
  - Location: state
  - Time: sale date

> Note: This dataset represents **second-hand (used) vehicle transactions**, not new car sales.

---

## 🔍 Analysis Questions Addressed

### 1. Brand & Regional Performance
- Which vehicle brands perform best across different states?
- How does sales volume and revenue vary by **make × state**?
- Are some brands region-specific leaders?

### 2. Used-Car Depreciation Trends
- How does resale price change with **vehicle age and mileage**?
- Which brands retain value better in the used-car market?

### 3. Pricing Efficiency vs Market Benchmark
- How does the actual selling price compare with **MMR valuations**?
- Which brands and age groups are consistently over- or under-priced?

### 4. Profitability Analysis (MMR-based Proxy)
- Which states generate higher margins per vehicle?
- How does profitability vary across brands and vehicle age segments?

---

## 📈 Key Insights

- **Newer used vehicles (0–7 years)** trade very close to market benchmarks, indicating a highly efficient and competitive pricing environment.
- **Pricing volatility increases significantly for older vehicles**, suggesting higher risk but also greater opportunity for skilled pricing strategies.
- **Brand-specific pricing behavior emerges at higher vehicle ages**, reinforcing the need for differentiated pricing models by manufacturer.
- **MMR reliability decreases for older vehicles**, highlighting the importance of manual overrides or adjusted valuation models in aged inventory.

---

## 🧠 Methodology Highlights
- Data cleaning and type correction for pricing fields
- Feature engineering (vehicle age, proxy profit percentage)
- Aggregation by meaningful business dimensions (make, state, age)
- LOWESS smoothing to extract long-term trends while reducing noise
- Filtering low-sample segments to avoid misleading tail effects

---

## 📊 Visualizations Included
- Brand-wise depreciation curves (price vs age)
- Pricing efficiency trends relative to MMR
- State-wise profitability comparisons
- Revenue and volume comparisons by manufacturer

All visualizations are designed to answer **“So what?”** from a business perspective.

---

## 🛠️ Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, statsmodels  
- **Tools:** Jupyter Notebook, GitHub  

---

