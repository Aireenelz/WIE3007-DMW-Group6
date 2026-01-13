WIE3007 – Data Mining & Warehousing  
Group 6 – Loan Default Prediction Project

This repository contains the coursework submission for **WIE3007: Data Mining & Warehousing**.  
The project focuses on developing and evaluating predictive models to identify loan default risk using structured and unstructured data.

## Project Objective
The main objective of this project is to:
- Build predictive classification models to identify whether a borrower is likely to default on a loan.
- Apply feature engineering techniques, including AI-assisted text processing.
- Evaluate and interpret model performance using appropriate machine learning metrics.


##  Dataset Overview
The dataset consists of:
- **Numerical features** (e.g. income, loan amount, credit score)
- **Categorical features** (e.g. employment status, loan purpose)
- **Text-based features** (loan purpose descriptions)

Text data is transformed using **TF-IDF vectorization** to capture semantic patterns relevant to default risk.

## ⚙️ Methodology
### 1. Data Preprocessing
- Missing value handling
- Feature scaling and encoding
- Train-test split with class balance preservation

### 2. Feature Engineering
- Debt-to-Income Ratio
- Loan Burden Indicator
- Credit Risk Flags
- TF-IDF text feature extraction (AI-assisted)

### 3. Model Development
- Random Forest Classifier
- Comparison between underfitting and higher-capacity models
- Pipeline-based implementation to prevent data leakage


## 📊 Model Evaluation
Models are evaluated using:
- **F1-score** (primary metric)
- **Accuracy** (supporting metric)
- **ROC-AUC** (discriminative performance)

## 🔍 Model Interpretation
- Feature importance analysis
- Financial risk insights based on model behaviour
- Interpretation supported by AI-assisted summarisation

🛠 Tools & Technologies
- Python
- Scikit-learn
- Pandas, NumPy
- TF-IDF (Text Feature Engineering)
- Jupyter Notebook
- GitHub (Version Control & Collaboration)

## 👥 Group Members
- Group 6 – WIE3007  
Ameera binti Omar
Aireen Elzahraa binti Ahmad Aljafri
Qurrata Ain Bt Mohd Khairi
Shum Joan
Athiyah Fahirah


## 📄 Notes
This repository demonstrates collaborative development through GitHub using pull requests, commits, and peer review comments, in line with course requirements.
