# Explainable Machine Learning for AQI Prediction

## Overview
This project focuses on predicting the Air Quality Index (AQI) using machine learning models and interpreting the predictions using Explainable AI techniques. The goal is to build transparent and reliable models for environmental monitoring.

## Dataset
The dataset contains daily air quality data for an Indian city, including:
- PM2.5
- PM10
- NO₂
- SO₂
- CO
- O₃
- AQI (target variable)

The data is sourced from publicly available Indian air quality datasets.

## Methodology
1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Model building using:
   - Linear Regression
   - Random Forest Regressor
4. Model evaluation using RMSE and R² score
5. Explainable AI analysis using SHAP

## Explainability
- Feature importance from Random Forest
- SHAP summary and dependence plots for global interpretability
- Local explanation of individual AQI predictions

## Results
The Random Forest model outperformed Linear Regression, capturing non-linear relationships in air pollutant data. PM2.5 and PM10 were identified as the most influential factors affecting AQI.

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- SHAP
- Matplotlib, Seaborn
- Google Colab

## Conclusion
This project demonstrates the importance of explainable machine learning in environmental applications, enabling accurate AQI prediction while maintaining transparency and interpretability.

## Project Outputs

### Correlation Heatmap
![Correlation](results/correlation_heatmap.png)

### Feature Importance
![Feature Importance](results/feature_importance.png)

### SHAP Summary Plot
![SHAP](results/shap_summary.png)

