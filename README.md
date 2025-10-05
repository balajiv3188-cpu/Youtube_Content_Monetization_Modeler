# Content Monetization Modeler

## Overview
This repository presents a solution for estimating **YouTube Ad Revenue** at the video level using various regression algorithms. The project is complemented by a user-friendly **Streamlit interface** for real-time prediction and data exploration.

## Problem Focus
YouTube creators rely heavily on ad revenue, making accurate earnings prediction essential for:
- Optimizing content strategies
- Forecasting revenue
- Enhancing creator support tools
- Planning ad campaigns

## Technologies Used
- Programming: Python
- Libraries: Pandas, Scikit-learn
- Machine Learning: Linear Regression, Decision Tree, Gradient Boosting, Random Forest, XGBoost
- Data Handling: Feature engineering, preprocessing, exploratory analysis (EDA), and visualization
- Frontend: Streamlit for web app deployment

## Data Details
- **Dataset**: YouTube Monetization Modeler (CSV, ~122k rows)
- **Dependent variable**: `ad_revenue_usd`
- **Features include**: views, likes, comments, watch time, video length, subscribers, category, device, country, and more

## Methodology
1. Clean and preprocess the dataset (addressing missing data, duplicates, encoding categorical values)
2. Engineer new features (e.g., calculate engagement rate as (likes + comments)/views)
3. Train five regression models and benchmark their predictive performance
4. Evaluate models using R², RMSE, and MAE metrics
5. Develop a user-facing Streamlit application for interaction and insight delivery

## Outcomes
- A refined dataset suitable for in-depth analysis
- Predictive regression models for estimating YouTube ad income
- An interactive Streamlit app offering:
  - Ad revenue prediction from custom input
  - Visualizations and model interpretability features
