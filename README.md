📊 Marketing Campaign Response Prediction & Dashboard

📌 Project Overview

This project predicts customer response to marketing campaigns using machine learning and translates model outputs into interactive Tableau dashboards. The goal is to help marketing teams identify high-probability customers and improve campaign targeting and effectiveness.

🧠 Problem Statement

Marketing campaigns are costly and often inefficient when targeted broadly. This project aims to:

* Predict which customers are likely to respond to a campaign
* Compare multiple machine learning models
* Use prediction probabilities to support data-driven targeting decisions

📂 Dataset

The dataset contains customer demographic, financial, and campaign interaction data, including:

* Customer attributes (age, job, education, balance, etc.)
* Campaign details (contact method, duration, previous outcomes)
* Response indicator (used during model training)

⚙️ Project Workflow

1. Data Cleaning & Feature Engineering
   * Handled missing values and categorical encoding
   * Prepared model-ready datasets
     
2. Model Training & Evaluation
   * Logistic Regression
   * Random Forest
   * XGBoost
   * Evaluated using ROC-AUC and classification metrics
     
3. Prediction & Targeting
   * Generated response probabilities
   * Identified high-probability customers for targeting
     
4. Data Export for Visualization
   * Created clean CSV outputs for Tableau
     
5. Dashboard Development
   * Built interactive dashboards to communicate insights

📊 Tableau Dashboards

Two dashboards were created:

1.Dashboard 1: Marketing Campaign Analysis

* Customer distribution by job and demographics
* Balance distribution by job
* Campaign and contact effectiveness
* Previous campaign outcome analysis

2.Dashboard 2: Model & Prediction Insights

* Actual response distribution
* Model probability distribution
* Model performance comparison
* High-probability customer segmentation

🗂️ Repository Structure

```
├── marketcampaignresponseprediction.ipynb   # Data prep & ML models
├── tableau_marketing_clean_data.csv         # Cleaned marketing data
├── tableau_predictions_clean.csv            # Model predictions
├── model_comparison.csv                     # Model performance metrics
├── marketingresponse.twb                    # Tableau workbook
└── README.md
```
🛠️ Tools & Technologies

* Python: Pandas, NumPy, Scikit-learn, XGBoost
* Visualization: Tableau
* Model Evaluation: ROC-AUC, classification metrics
* Version Control: Git & GitHub

🚀 Key Takeaways

* Machine learning can significantly improve marketing targeting
* Probability-based predictions are more actionable than binary outputs
* Tableau enables effective communication of complex ML results to non-technical stakeholders

📌 Future Improvements

* Add cost-benefit analysis for campaign decisions
* Deploy model as an API
* Automate dashboard refresh with live data

👤 Author
Sarah Tondle
Data Science / Analytics Portfolio Project


* Review your dashboards like a hiring manager
* Make a **short “How to use this repo” section**
