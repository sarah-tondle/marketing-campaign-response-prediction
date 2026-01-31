📊 Marketing Campaign Response Prediction & Dashboard

📌 Project Overview

This project predicts customer responses to marketing campaigns using machine learning and translates model outputs into interactive Tableau dashboards. The objective is to help marketing teams identify high-probability customers and improve campaign targeting efficiency through data-driven decision-making.

🧠 Problem Statement

Marketing campaigns are expensive and often inefficient when broadly targeted. This project aims to:

Predict which customers are most likely to respond to a campaign

Compare multiple machine learning models for predictive performance

Use probability-based predictions to support smarter customer targeting

📂 Dataset

The dataset includes customer demographic, financial, and campaign interaction data such as:

Customer attributes: age, job, education, account balance, etc.

Campaign details: contact method, duration, previous campaign outcomes

Response indicator (used during model training)

📌 Data Source:
UCI Machine Learning Repository – Bank Marketing Dataset
(Referenced in DATA_SOURCE.md; raw data is not redistributed.)

⚙️ Project Workflow
1️⃣ Data Cleaning & Feature Engineering

Handled missing and unknown values

Encoded categorical variables

Prepared model-ready datasets

2️⃣ Model Training & Evaluation

Trained and evaluated multiple models:

Logistic Regression

Random Forest

XGBoost

Evaluation Metric: ROC-AUC and classification metrics

3️⃣ Prediction & Targeting

Generated customer response probabilities

Identified high-probability customers for targeted campaigns

4️⃣ Data Export for Visualization

Created clean, analysis-ready CSV files for Tableau

5️⃣ Dashboard Development

Built interactive dashboards to communicate insights to business stakeholders

📊 Tableau Dashboards
Dashboard 1: Marketing Campaign Overview

Customer distribution by job and demographics

Balance distribution by job

Contact method and campaign effectiveness

Previous campaign outcome analysis

Dashboard 2: Predictive Model & Targeting Insights

Actual response distribution

Model probability distribution

Model performance comparison (ROC-AUC)

High-probability customer segmentation

🗂️ Repository Structure
├── marketcampaignresponseprediction.ipynb   # Data preparation & ML modeling
├── tableau_marketing_clean_data.csv         # Cleaned marketing dataset
├── tableau_predictions_clean.csv            # Model prediction outputs
├── model_comparison.csv                     # Model performance metrics
├── marketingresponse.twb                    # Tableau workbook
├── DATA_SOURCE.md                           # Dataset reference & attribution
└── README.md

🛠️ Tools & Technologies

Python: Pandas, NumPy, Scikit-learn, XGBoost

Visualization: Tableau

Model Evaluation: ROC-AUC, classification metrics

Version Control: Git & GitHub

🚀 Key Takeaways

Machine learning enables more effective marketing targeting

Probability-based predictions are more actionable than binary outcomes

Tableau bridges the gap between advanced analytics and business decision-making

📌 Future Improvements

Add cost-benefit analysis for campaign decisions

Deploy the model as an API

Automate dashboard refresh with live or streaming data
