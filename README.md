This repository contains a data analysis / machine learning workflow centered on **detecting credit card fraud** in a highly **imbalanced dataset**.  


---

## 🎯 Project Overview

**Goal:**  
To build and evaluate models that can effectively detect fraudulent credit card transactions, particularly when fraud instances are extremely rare compared to non-fraud ones.

**Challenges:**
- Severe class imbalance (fraud << non-fraud)
- Risk of overfitting
- Importance of choosing appropriate metrics (precision, recall, F1, ROC-AUC, PR-AUC)
- Data preprocessing and feature scaling

**Approach & Highlights:**
- Exploratory Data Analysis (EDA) to understand distributions, feature correlations, and anomalies  
- Data preprocessing: scaling, handling skewed features  
- Multiple resampling techniques:
  - Random Oversampling  
  - Random Undersampling  
  - SMOTE / ADASYN  
  - Combination methods  
- Model training & comparison:
  - Logistic Regression  
  - Random Forest  
  - XGBoost / LightGBM  
- Evaluation on multiple metrics (ROC-AUC, PR curve, recall for fraud class)  
- Visualization & interpretation of results  

---

## 🛠 Getting Started

### Prerequisites

You need:

- Python ≥ 3.8  
- `pip` or `conda`  
- Basic ML / data science libraries: `numpy`, `pandas`, `scikit-learn`, `imbalanced-learn`, `matplotlib`, `seaborn`, `xgboost`, etc.

You can optionally use a `requirements.txt` or `environment.yml` file:

```bash
pip install -r requirements.txt

