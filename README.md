# End-to-End Telco Customer Churn Prediction & BI Pipeline

An end-to-end data science and business intelligence project that predicts telecom customer churn using Machine Learning and visualizes risk density through an interactive Power BI dashboard.

## 🚀 Project Overview
This project builds a predictive pipeline to flag high-risk telecom accounts. By connecting a Python-based predictive model with Power BI via custom index mapping, it translates complex ML outputs into actionable customer retention strategies.

## 🛠️ Tech Stack & Tools
- **Language:** Python (Pandas, NumPy, Scikit-Learn)
- **Machine Learning:** Logistic Regression
- **Business Intelligence:** Power BI Desktop, Power Query

## 📊 Key Insights & Business Impact
- **The High-Risk Zone:** Identified that new customers (0-20 months tenure) with high monthly charges (>$70) have the highest density of predicted churn.
- **Critical Retention Timeline:** Discovered that the average tenure of volatile customers is **16.44 months**, highlighting that retention strategies must be deployed around the 12th month mark.
- **Safe Zone:** Verified that customers with lower monthly charges (~$20) or those with long tenures (>60 months) show minimal churn risk.

## 📁 Repository Structure
- `py_notebook/`: Python notebooks for data preprocessing and model building.
- `bi_dashboard/`: Power BI dashboard (`.pbix` file).

## 💡 How to Run
1. Run the Python notebook to generate the `Predicted_Churn` outputs.
2. Open the `.pbix` file in Power BI Desktop to explore the interactive dashboard and its data models.
