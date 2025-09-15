# Integrated-Retail-Analytics-for-Store-Optimization
Retail Analytics Project: An end-to-end pipeline for sales anomaly detection, time-series forecasting, customer segmentation, and market basket analysis. Delivers data-driven insights for inventory optimization, pricing, and personalized marketing strategies.


# 🛒 Retail Analytics for Store Optimization  

## 📌 Project Overview  
This project builds a comprehensive **Retail Analytics Pipeline** to analyze, forecast, and optimize sales across multiple stores and departments. Using machine learning and statistical techniques, the project provides **insights for inventory management, marketing strategies, and store-level decision-making**.  

---

## 🎯 Problem Statement  
Retailers generate massive amounts of sales, store, and feature data, but face challenges in:  
- Detecting **anomalies** in sales caused by holidays, markdowns, or external factors.  
- Understanding **seasonality and time-based variations** in performance.  
- Designing **customer/store segmentation** for targeted strategies.  
- Forecasting **future sales and demand** at granular levels.  
- Leveraging **external indicators** (CPI, unemployment, fuel prices) for better decision-making.  

This project addresses these gaps by developing a data-driven, end-to-end analytics framework.  

---

## ⚙️ Project Components  

1. **Data Preprocessing & Feature Engineering**  
   - Handle missing values (esp. MarkDowns).  
   - Create lag, rolling, seasonal, and anomaly detection features.  

2. **Anomaly Detection**  
   - Identify unusual sales at store/dept level using z-score and time-series decomposition.  
   - Handle anomalies (impute, cap, drop, or flag).  

3. **Time-Based Analysis**  
   - Seasonal decomposition to extract trends & seasonality.  
   - Analyze holiday vs non-holiday sales.  

4. **Customer Segmentation**  
   - KMeans clustering for store and department segmentation.  
   - Evaluate quality using silhouette and Davies-Bouldin scores.  

5. **Market Basket Analysis**  
   - Apply Apriori algorithm to infer department associations.  
   - Generate association rules and cross-sell insights.  

6. **Demand Forecasting**  
   - XGBoost regression for store–department level forecasting.  
   - Prophet models for time-series based forecasting.  
   - Compare models using RMSE & R².  

7. **Impact of External Factors**  
   - Regression & feature importance analysis with CPI, Fuel Price, and Unemployment.  

8. **Personalization & Strategy**  
   - Generate recommendations for each store cluster.  
   - Suggest inventory actions based on forecast growth.  

---

## 📊 Deliverables  

- Cleaned & feature-rich datasets (`df_cleaned_for_modeling.csv`, `df_features_for_modeling.csv`).  
- Store and department **segmentation profiles**.  
- **Association rules** and frequent itemsets for cross-sell strategies.  
- **Forecasting models** (XGBoost, Prophet) saved for deployment.  
- Cluster-based and store-dept level **recommendation reports**.  
- Visualizations for trends, anomalies, and sales drivers.  

---

## 🛠️ Tools & Techniques  

- **Python Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, mlxtend, xgboost, prophet  
- **Machine Learning**: KMeans, XGBoost, Apriori  
- **Time-Series Analysis**: Seasonal Decomposition, Prophet  
- **Evaluation Metrics**: RMSE, R², Silhouette Score, Davies-Bouldin Score  

---

## 📈 Key Insights  

- Sales peaks strongly around holidays (Nov/Dec).  
- Markdown strategies significantly influence sales in some clusters.  
- Certain departments consistently outperform others across stores.  
- External economic factors like CPI & Unemployment have measurable impact on demand.  
- Forecasting models enable proactive inventory and promotional planning.  

---




