# 📊 Data-Driven Sales Forecasting & Discount Optimization for E-Commerce

## 🔍 Project Summary
This project develops a data-driven pricing intelligence framework that combines **machine learning** and **causal inference** to improve discount decision-making in e-commerce.

It addresses a critical business question:
> Do discounts actually drive incremental sales, or do they simply shift demand and erode margins?

The solution moves beyond traditional analytics by integrating **forecasting, causal estimation, and optimization** into a unified pipeline.

---

## 🎯 Business Context
In most e-commerce environments:
- Discounts are applied broadly during campaigns and festive periods
- Decisions are often based on conversion trends rather than true impact
- Lack of demand forecasting leads to inefficient pricing strategies

This results in:
- Margin leakage  
- Misallocation of promotional budgets  
- Over-reliance on intuition  

This project aims to replace assumption-driven decisions with **evidence-based pricing strategies**.

---

## ⚙️ Solution Approach

### 1. Demand Forecasting
Built predictive models to estimate product-level sales using:
- Pricing and discount variables  
- Product ratings and category features  
- Historical demand (lag features)  

**Models implemented:**
- XGBoost (primary model)
- Random Forest (validation model)

---

### 2. Causal Impact Estimation
Applied **Double Machine Learning (DML)** to estimate the *true causal effect* of discounts on sales.

This allows separation of:
- Correlation (what appears to work)
- Causation (what actually drives results)

---

### 3. Discount Optimization
- Segmented products based on discount responsiveness  
- Targeted high-response segments for promotions  
- Simulated optimized pricing policy vs baseline  

---

## 📊 Results & Performance

| Metric | Value |
|------|------|
| R² (Forecasting Accuracy) | ~0.96 |
| MAE | Low error range |
| % Products with Positive Discount Impact | ~43% |
| % Products with Negative/Neutral Impact | ~57% |
| Projected Revenue Gain | ₹1.95 Billion |

---

## 💡 Key Insights

- Blanket discounting is often counterproductive  
- A majority of products do not benefit from price reductions  
- Targeted discounting significantly improves efficiency and ROI  
- Combining ML with causal inference enables better business decisions  

---

## 🛠️ Tech Stack

- Python  
- XGBoost  
- Random Forest  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib  

---

## 📂 Data Source
Amazon UK Products Dataset (Kaggle)  
Includes product-level pricing, discounting, ratings, and temporal sales data

---

## 🧪 Methodological Rigor

- Time-based train-test split to prevent leakage  
- Lag feature engineering for temporal dependencies  
- Cross-validation for generalization  
- Causal estimation using orthogonalized DML framework  

---

## 📈 Business Impact

This framework enables:
- More efficient allocation of discount budgets  
- Reduction in unnecessary promotions  
- Improved pricing precision  
- Better alignment between marketing and revenue outcomes  

---

## 🔮 Future Scope

- Reinforcement learning for dynamic pricing  
- Integration of competitor pricing signals  
- Inventory-constrained optimization  
- Real-time deployment pipelines  

---

## 👥 Contributors

- Debjyoti Basu  
- Yougantar Dutta  
- Kshitika Agarwal  

**Guided by Prof. Suman Sanyal**  
Goa Institute of Management

---

## 🔗 Repository
👉 https://github.com/debjyotibasu123/Data-Driven-Sales-Prediction-and-Pricing-Optimization-for-E-Commerce-Platforms-

---

## ⭐ Acknowledgement
If you find this project insightful, feel free to star the repository.
