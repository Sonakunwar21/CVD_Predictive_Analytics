<div align="center">

# ❤️ Cardiovascular Risk Assessment & Predictive Analytics

### Healthcare Data Analysis • Machine Learning • Predictive Analytics

<p>
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikit-learn&logoColor=white">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/Healthcare-Analytics-0EA5E9">
</p>

<p>
A healthcare-focused data science project exploring cardiovascular risk factors  
and building machine learning models to predict the presence of cardiovascular disease.
</p>

</div>

---

## 📌 Project Overview

This project analyzes the **Kaggle Cardiovascular Disease Dataset** to understand how demographic, physiological, metabolic, and lifestyle factors are associated with cardiovascular disease.

The project follows an end-to-end data science workflow:

> **Data Understanding → Data Cleaning → Feature Engineering → EDA → Machine Learning → Model Evaluation → Feature Importance → Medical Interpretation**

**The main objective** was to understand the patterns in cardiovascular disease data and evaluate whether these factors could be used to classify CVD presence.

---

## 🎯 Research Question

> **Which demographic, physiological, metabolic, and lifestyle factors are associated with cardiovascular disease, and can these factors be used to predict CVD presence?**

---

## 📊 Dataset

| Detail | Information |
|---|---|
| Source | [Kaggle – Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset) |
| Original Records | **70,000** |
| Original Features | **13** |
| Target | `cvd` |
| Problem Type | **Binary Classification** |

### Main Feature Groups

| Group | Variables |
|---|---|
| 👤 **Demographic** | Age, Gender |
| 🩺 **Physiological** | Height, Weight, Systolic BP, Diastolic BP, BMI, Pulse Pressure |
| 🧪 **Metabolic** | Cholesterol, Glucose |
| 🚶 **Lifestyle** | Smoking, Alcohol Use, Physical Activity |
---
## 🔍 Project Workflow

`Data Understanding`
→ `Data Cleaning`
→ `Feature Engineering`
→ `EDA`
→ `ML Preprocessing`
→ `Logistic Regression`
→ `Random Forest`
→ `Hyperparameter Tuning`
→ `Model Evaluation`
→ `Threshold Analysis`
→ `Feature Importance`
→ `Medical Interpretation`

---

## 📈 Key EDA Findings

> 🩺 **Age:** CVD prevalence increased consistently across older age groups.

> 🩸 **Blood Pressure:** Higher BP categories showed a strong increase in CVD prevalence.

> ⚖️ **BMI:** CVD prevalence increased from lower BMI groups toward overweight and obesity.

> 🧪 **Cholesterol:** Higher cholesterol categories showed substantially higher CVD prevalence.

> 🚶 **Physical Activity:** Inactive participants showed somewhat higher CVD prevalence than active participants.

> 🔗 **Combined Factors:** Age + BP and BMI + physical activity showed meaningful combined patterns with CVD prevalence.

---

## 🤖 Machine Learning Results

Two models were evaluated on the same held-out test set.

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 71.47% | 72.82% | 67.55% | 70.09% | 77.90% |
| **Random Forest** | **72.93%** | **74.76%** | **68.37%** | **71.43%** | **79.56%** |

### 🏆 Final Model

**Tuned Random Forest Classifier**

Best parameters:

```text
n_estimators      = 300
max_depth         = 12
min_samples_split = 2
```
## 🧠 What This Project Demonstrates

- End-to-end **healthcare data analysis** from raw data to insights
- Data cleaning and **domain-based feature engineering**
- Univariate, bivariate, and multivariate **EDA**
- Binary classification using **Logistic Regression and Random Forest**
- **Cross-validation and hyperparameter tuning**
- Model evaluation using **Accuracy, Precision, Recall, F1-Score, ROC-AUC, ROC and PR curves**
- **Threshold analysis** with a focus on Recall / Sensitivity
- Model interpretation using **feature importance, permutation importance, and Logistic Regression coefficients**
- Ability to translate ML results into **clear, general medical insights**
- Understanding of the difference between **association and causation**

---

## 👩‍💻 Author

### **Sona Kunwar**
 *Turning data into meaningful and actionable insights.*
 
