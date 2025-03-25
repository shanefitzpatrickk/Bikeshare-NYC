# 🚲 NYC Bikeshare Analysis

Shane Fitzpatrick 

## 📌 Overview
This project explores NYC Bikeshare data (2015–2017) to help the Department of Transportation understand trends in usage, rider behavior, and station demand. It includes data cleaning, visual exploration, regression analysis, and geospatial calculations.

## 🧠 Research Questions
1. **When do people ride the most?**  
   → Visualized daily trip volume to detect seasonality and trends.

2. **Do older riders take longer trips?**  
   → Used scatterplots and linear regression to explore age vs. duration.

3. **Can we predict trip distance?**  
   → Engineered a `distance` feature using the Haversine formula and modeled it via OLS regression.

4. **Where is demand the highest?**  
   → Identified top stations based on trip volume to guide resource allocation.

## 📊 Key Tools
- `pandas`, `numpy` for data wrangling  
- `matplotlib`, `seaborn` for visualizations  
- `statsmodels` for regression analysis  
- Jupyter for clean, annotated storytelling

## 🎯 Insights
- Bikeshare activity has clear temporal trends.
- Younger users tend to ride longer.
- Demand prediction is viable using available features.
- Grove St PATH is the most popular station, with actionable implications for supply.

## 🧰 Next Steps
- Incorporate weather and seasonality into demand models  
- Cluster user types by behavior  
- Deploy dashboards for real-time planning
