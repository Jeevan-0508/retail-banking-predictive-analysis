# 🏦 Predictive Analytics for Retail Banking

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?style=flat-square&logo=scikit-learn)
![Node-RED](https://img.shields.io/badge/Node--RED-Flow-red?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

> End-to-end predictive analytics pipeline for retail banking — classifying customer risk and predicting defaults using machine learning and a Node-RED interactive dashboard.

## 📌 Problem Statement
Retail banks face mounting pressure to proactively identify customers at risk of default or financial distress. This project builds a classification model that predicts risk outcomes from customer transaction and demographic data, paired with a real-time Node-RED UI.

## 🎯 Key Objectives
- Predict customer default/risk using supervised ML
- Perform deep EDA on banking behavioural patterns
- Deploy an interactive Node-RED flow for live predictions
- Visualise risk distribution across customer segments

## 🔬 Models Used
| Model | Notes |
|-------|-------|
| Logistic Regression | Interpretable, regulatory-friendly baseline |
| Random Forest | Feature importance + low variance |
| Decision Tree | Rule extraction for compliance |
| XGBoost | High accuracy, handles imbalanced classes |

## 🗂️ Dataset
`bank.csv` — retail banking customer data (demographics, account history, credit behaviour)

## 🛠️ Tech Stack
`Python` · `pandas` · `scikit-learn` · `XGBoost` · `Node-RED` · `Jupyter`

## 📊 Architecture
```
bank.csv → EDA → Feature Engineering → Model Training
                                              ↓
            Logistic Reg / RF / XGBoost / Decision Tree
                                              ↓
                     Risk Scoring → Node-RED Dashboard
```

## 📸 Screenshots
| Node-RED Flow | ML Model UI |
|---|---|
| ![Flow](Node%20Red%20Flow.png) | ![UI](ML%20Model%20UI.png) |

## 🚀 Run Locally
```bash
pip install pandas scikit-learn xgboost matplotlib seaborn jupyter
jupyter notebook "Predictive Analytics For Retail Banking .ipynb"
```

## 🔗 Relevance to Risk Management
This project mirrors real-world risk workflows used by banks to automate credit decisioning — directly applicable to fraud risk, credit risk, and regulatory compliance.

---
*Jeevan Siddha Bhaktula · Risk & Data Science Portfolio*
