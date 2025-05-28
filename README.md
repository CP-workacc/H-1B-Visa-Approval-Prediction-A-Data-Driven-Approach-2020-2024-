# H-1B-Visa-Approval-Prediction-A-Data-Driven-Approach-2020-2024-
Analyze 3.5M+ H-1B visa applications (2020–2024) using ML (XGBoost, Random Forest) to predict denials and uncover key trends in wage levels, roles, and employer compliance. Insights support hiring, job search, and policy evaluation.

## 📌 Overview

Using models like **Random Forest** and **XGBoost**, this study identifies influential factors behind visa decisions — including job title, wage, cost of living, and employer history. The project combines preprocessing, statistical analysis, visualization, and modeling to produce reliable and explainable results.

## 🧠 Key Features

- Cleaned and merged multi-source datasets including wage, employer, cost of living, and crime data  
- Built classification models to predict visa approval/denial outcomes  
- Engineered features such as `wage_to_cost_ratio` and `crime_risk_score`  
- Delivered insights on industry trends, employer compliance, and geographic factors  
- Visualized findings using clear, stakeholder-friendly plots and dashboards

## 📂 Research Question Structure

The project addresses **Research Questions 1–6**, with each question explored in a dedicated Jupyter notebook.

### 📘 Notebooks:
- `RQ_01.ipynb`  
- `RQ_02.ipynb`  
- `RQ_03.ipynb`  
- `RQ_04.ipynb`  
- `RQ_05.ipynb`  
- `RQ_06.ipynb`

📁 All notebooks are stored in the `notebooks/` directory.

## 🔗 Dataset Integration: Cost of Living & Crime Analysis

To enhance geographic and socioeconomic understanding:
- Merged **cost of living indices** and **crime rate data** using `worksite_city` and `worksite_state`
- Created features such as:
  - `wage_to_cost_ratio` = prevailing wage / cost of living index
  - `crime_risk_score` = violent crimes + weighted property crimes
- Enabled localized insights into visa approval trends by region

## 🛠 Tech Stack

- **Languages**: Python (Pandas, NumPy, Scikit-learn, XGBoost)
- **Visualization**: Matplotlib, Seaborn
- **Tools**: Jupyter Notebook, VS Code
- **Data Platforms**: AWS Redshift, Azure, PostgreSQL

## 📊 Outcomes

- Identified top predictors of visa denials
- Built explainable ML models to flag high-risk applications
- Generated insights for hiring strategy and immigration policy refinement

