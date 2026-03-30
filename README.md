# 🏦 Loan Default Prediction using Explainable AI (SHAP & LIME)

An interpretable machine learning framework for predicting loan defaults using multiple models and hybrid ensembles, enhanced with SHAP and LIME for transparency.

---

## 🚀 Overview

Accurate credit risk assessment is critical in digital lending. This project builds a **machine learning + explainability framework** to:

- Predict loan defaults
- Improve detection of high-risk borrowers
- Provide interpretable decision insights

---

## 📂 Dataset

- **LendingClub Loan Dataset (2007–2018)**
- 1.34 million records
- 21 selected features
- Class distribution:
  - ~75% non-default
  - ~25% default :contentReference[oaicite:1]{index=1}

---

## 🧠 Models Used

| Model              | Description |
|-------------------|------------|
| Logistic Regression | Baseline interpretable model |
| Decision Tree       | Rule-based classification |
| Random Forest       | Ensemble learning |
| XGBoost             | High-performance boosting |
| TabNet              | Deep learning for tabular data |
| Hybrid Stacking     | Ensemble meta-model |
| Hybrid2             | Dynamic hybrid model |

---

## ⚙️ Key Features

- 📊 Large-scale financial dataset handling
- ⚖️ Class imbalance handled using **SMOTE**
- 🧠 Hybrid ensemble models
- 🔍 Explainability using:
  - SHAP (global + local)
  - LIME (instance-level)
- 📈 Threshold tuning for improved recall

---

## 📊 Results

|     Model           | Accuracy | Recall | F1 Score | ROC-AUC |
|---------------------|---------|--------|---------|--------|
| Logistic Regression | 0.6497 | 0.5858 | 0.4004 | 0.6796 |
| Random Forest       | 0.7143 | 0.4467 | 0.3844 | 0.6861 |
| XGBoost             | 0.7962 | 0.1244 | 0.1960 | 0.6986 |
| Hybrid Stacking     | 0.6390 | **0.6372** | **0.4134** | 0.6910 |
| Hybrid2             | 0.7045 | 0.4783 | 0.3926 | 0.6881 |

---

## 🔍 Explainable AI

### SHAP
- Global feature importance
- Local prediction explanations

### LIME
- Instance-level interpretability
- Helps understand individual borrower risk

---

## 🧩 Workflow

1. Data preprocessing & feature selection  
2. Handling missing values & encoding  
3. SMOTE-based balancing  
4. Model training & evaluation  
5. Hybrid ensemble creation  
6. Explainability integration  

---

## 📌 Key Insights

- XGBoost achieves highest accuracy but **low recall**
- Hybrid models significantly improve **default detection**
- Explainability improves **trust and transparency**

---

## 🛠️ Tech Stack

- Python
- Scikit-learn
- XGBoost
- TabNet
- SHAP
- LIME
- Pandas, NumPy

---

## 🔮 Future Work

- Apply Transformer-based tabular models
- Improve recall without sacrificing precision
- Combine XAI with rule-based systems
- Deploy as real-time credit scoring system

---


## 👩‍💻 Author

- Sakshi 

---
