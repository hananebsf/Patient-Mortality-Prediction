# Patient Mortality Prediction 🚑💡

## Project Overview

This project aims to predict patient mortality within 180 days following their last recorded medical examination using Electronic Health Records (EHR). The goal is to develop an end-to-end machine learning pipeline that processes EHR data, engineers predictive features, and applies machine learning algorithms to improve predictive accuracy.

This project is inspired by the [EHR Dream Challenge 2019](https://www.synapse.org/#!Synapse:syn18405991/wiki/589657), organized by the **University of Washington and Sage Bionetworks**.

## Dataset 📊

Since the original challenge dataset is restricted due to privacy regulations, we are using a synthetic dataset based on Synpuf (Synthetic Public Use File) provided by CMS (Centers for Medicare and Medicaid Services). The data follows the OMOP Common Data Model (CDM) standard.

The dataset is available in CSV format.
It is split into training and testing sets.
Data includes tables on patient demographics, conditions, visits, drugs, and lab tests.
📂 Download Dataset: [Link IN PROGRESS]
📖 Concept Codes: OHDSI Athena
📖 OMOP Common Data Model: OHDSI Documentation

## Project Goals & Learning Objectives 🎯

Through this project, we aim to:

Explore an EHR dataset and understand its structure.
Perform feature engineering to extract relevant features.
Join multiple datasets to build a coherent dataframe for machine learning.
Train different ML models and compare their performance.
Evaluate models using appropriate classification metrics.

## Feature Engineering 🔬

Key features extracted from the EHR dataset include:

Demographics: Age, Gender, Race (from the person table).
Medical Conditions: Chronic or life-threatening diseases (e.g., cancer, COPD, renal failure, AIDS).
Comorbidity Index: Charlson Comorbidity Index (CCI) to quantify disease burden and mortality risk.
Visit History: Number of past hospital visits, ICU admissions, etc.
Medication Data: Prescribed drugs and treatment history.
Machine Learning Approach 🤖

## We implement various classification algorithms using scikit-learn
## Model Evaluation 📈

Since this is a binary classification task, we evaluate models using standard metrics:

- Precision
- Recall
- F1-score
- ROC-AUC Curve

## Project Structure 📂

### 📦 Patient-Mortality-Prediction

├── 📜 README.md  

├── 📂 data  # Dataset (train/test CSVs)

├── 📜 Patient Mortality Prediction Report.pdf  # Final Report

├── 📜 Patient Mortality Prediction code.ipynb  # Code Notebook

└── 📜 Presentation.pptx  # Project Presentation

## References & Acknowledgments 📚

- [EHR Dream Challenge 2019](https://www.synapse.org/#!Synapse:syn18405991/wiki/589657),: University of Washington & Sage Bionetworks
- [OMOP Common Data Model](https://ohdsi.github.io/CommonDataModel/): OHDSI
- Concept Codes:  [Athena OHDSI](https://athena.ohdsi.org/search-terms/start)
- [Charlson Comorbidity Index (CCI)](https://www.mdcalc.com/charlson-comorbidity-index-cci): MDCalc 
