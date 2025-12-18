# Bitcoin Price Forecasting – MLOps Final Project

This repository contains the complete workflow for a **Bitcoin price forecasting project**, covering data exploration, feature engineering, model development, evaluation, and deployment insights. The project follows an end-to-end **MLOps mindset**, from raw data ingestion to monitoring model behavior.

---

## Repository Structure & File Descriptions

### Data & Feature Engineering

- **Bitcoin_history_data.csv**  
  Raw historical Bitcoin price data used as the foundation for analysis and modeling.

- **btc_features.csv**  
  Dataset containing all engineered features derived from the raw historical data. This includes technical indicators and transformed variables created during feature engineering.

- **btc_features_forecast.csv**  
  Refined feature set used specifically for forecasting. Features were selected based on importance, redundancy reduction, and overlap analysis to improve predictive performance.

---

### Modeling & Evaluation

- **BitcoinFinal.ipynb**  
  The core notebook containing the **full pipeline for feature engineering and model development**. This includes preprocessing, feature selection, model training, and evaluation for Bitcoin price forecasting.

- **df_test.csv**  
  Test dataset used to evaluate the trained model under standard conditions.

- **changed_df_test.csv**  
  Modified version of the test dataset created after experimenting with feature changes to analyze model sensitivity and robustness.

---

### Exploratory Data Analysis (EDA)

- **BitcoinEDA.ipynb**  
  Exploratory Data Analysis of the raw Bitcoin historical data. This notebook includes visualizations, trend analysis, and statistical insights that informed feature engineering and modeling decisions.

---

### Deployment & Monitoring

- **Model_Monitoring.ipynb**  
  Contains deployment-related insights and model diagnostics, including model performance and behavior analysis generated using **Evidently reports** (evidently_baseline_ref.pdf and evidently_baseline_ref_vs_changed.pdf)

---

### Presentation

- **Final MLOps Project.pptx**  
  Presentation summarizing the Bitcoin forecasting problem, methodology, feature engineering process, modeling approach, results, and the overall MLOps workflow.

---

## Project Overview

This project aims to forecast Bitcoin prices using historical data and engineered features while demonstrating best practices in:

- Data exploration and preprocessing  
- Feature engineering and selection  
- Model training and evaluation  
- Feature robustness experimentation  
- Model monitoring and reporting using Evidently  

The repository is structured to clearly separate raw data, engineered datasets, modeling notebooks, and deployment insights to ensure transparency and reproducibility.
