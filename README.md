# 📊 Market Mix Modelling (MMM) using OLS Regression

## 🔍 Project Overview
This project builds an interpretable OLS-based Market Mix Model (MMM) to quantify the impact of various marketing channels on sales and provide ROI-driven budget allocation recommendations.

The model helps answer:

- Which marketing channels drive sales?
- How much does each channel contribute?
- Where should marketing budgets be optimized?

## 🎯 Business Objective
- Understand channel-level sales contribution
- Calculate ROI for each marketing channel
- Recommend optimal budget reallocation

## 📁 Dataset
- Monthly marketing & sales data (48 observations)
- **Target variable:** `kpi_val_sales_mn`
- **Media channels:** TV, Digital (Google, YouTube, FB/IG), Promotions, OTT, etc.
- **Control variables:** Distribution metrics

## 🧠 Methodology
1. Data cleaning & preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Multicollinearity check (VIF)  
4. Time-based train-test split  
5. OLS-based MMM  
6. Model validation (MAE, RMSE, R² – directional use)  
7. Contribution & ROI calculation  
8. Budget allocation recommendations  

## 📈 Model Validation (Test Data)
- **MAE:** 90.35  
- **RMSE:** 120.85  
- **R²:** Interpreted cautiously due to noise & short time series  

> **Note:** In MMM, directional accuracy and interpretability are prioritized over predictive R².

## 💡 Key Insights
- Not all high-spend channels generate high ROI  
- Some digital channels deliver strong efficiency at lower spend  
- Traditional media shows diminishing returns  

## 💼 Business Recommendations
- Increase or maintain spend on high-ROI channels  
- Optimize or reduce low-ROI channels  
- Reallocate budgets to maximize overall sales impact  

## ⚠️ Limitations & Future Scope
- No adstock or saturation modeling  
- Linear OLS assumptions  
- Short time series (48 months)  

### Future Improvements
- Adstock & Hill transformations  
- Bayesian MMM  
- Longer historical data  

## 🛠️ Tools & Libraries
Python, Pandas, NumPy, Statsmodels, Matplotlib, Seaborn

---

📌 This project was completed as part of an interview assignment for a Marketing Analytics / MMM role.
