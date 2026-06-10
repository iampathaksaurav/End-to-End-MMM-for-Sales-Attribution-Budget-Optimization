# End-to-End Marketing Mix Modeling (MMM) using Python

This project demonstrates a complete Marketing Mix Modeling (MMM) pipeline to analyze the impact of marketing channels on sales and support data-driven budget optimization decisions.

## 🔍 Project Overview

The model quantifies the contribution and efficiency (ROI) of various marketing channels such as TV, Radio, Print, and Internet by applying industry-standard transformations and regression techniques.

## ⚙️ Methodology

- Data Cleaning and Preprocessing  
- Feature Engineering:
  - Lag creation to capture delayed effects  
  - Adstock transformation to model carryover effect  
  - Saturation transformation to capture diminishing returns  
- Exploratory Data Analysis (EDA)
- Model Building:
  - Linear Regression (baseline)  
  - Ridge Regression (handling multicollinearity)  
  - Lasso Regression (feature selection)  
- Model Evaluation using time-based validation  
- Contribution Analysis and ROI Calculation  

## 📊 Key Components

- Marketing Channel Impact Analysis  
- Sales Attribution  
- ROI-based Budget Optimization  

## 📈 Outputs

- Actual vs Predicted Sales Visualization  
- Channel Contribution (%)  
- ROI by Marketing Channel  

## 💡 Objective

The goal is to build a structured, reusable MMM framework that captures real-world marketing dynamics and translates model outputs into actionable insights for business decision-making.

## 🛠️ Tools Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📌 Notes

This project focuses on demonstrating the end-to-end MMM workflow including feature engineering, modeling, and interpretation, with emphasis on real-world applicability.
