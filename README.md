# Credit Risk Analysis and Forecasting

## Overview
This project implements a comprehensive framework for **Credit Risk Analysis** and **Financial Forecasting**, focusing on US consumer loan portfolios. It incorporates **machine learning models** to calculate key risk metrics such as **Probability of Default (PD)**, **Loss Given Default (LGD)**, and **Expected Credit Loss (ECL)**. Additionally, it leverages **SARIMA models** for forecasting default rates and evaluates macroeconomic impacts using CCAR-like stress testing.

---

## Features
- **Credit Risk Modeling**:
  - Built **Gradient Boosting Classifiers** to predict **Probability of Default (PD)** with a **ROC-AUC score of 0.87**.
  - Developed regression models to estimate **Loss Given Default (LGD)** with an **MSE of 0.03**.

- **Expected Credit Loss (ECL)**:
  - Integrated **IFRS9/CECL frameworks** to calculate ECL based on PD, LGD, and EAD.

- **Financial Forecasting**:
  - Forecasted default rates using **SARIMA models** with RMSE of 0.02.
  - Conducted macroeconomic stress testing to evaluate risk in adverse scenarios.

- **Data Visualization**:
  - Created dynamic dashboards and visualizations for key credit risk metrics and forecasts.

---

## Technologies Used
- **Programming Languages**: Python
- **Machine Learning**: Gradient Boosting, Random Forest
- **Statistical Modeling**: SARIMA, Regression Analysis
- **Libraries**: pandas, numpy, scikit-learn, statsmodels, matplotlib, seaborn
- **Database Tools**: Presto, Hive
- **BI Tools**: Tableau, Power BI

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-risk-analysis.git
   cd credit-risk-analysis
