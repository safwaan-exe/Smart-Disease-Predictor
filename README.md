# Heart Disease Risk Prediction System (Machine Learning + Deep Learning + Explainable AI)

A complete end-to-end **Heart Disease Prediction System** built using classical ML models, a custom **Artificial Neural Network (ANN)**, and **Explainable AI (SHAP)**.  
This project performs full **data analysis → preprocessing → model training → evaluation → interpretability → deployment** with a Streamlit web app.

---

## 🏷️ Project Status  

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![NumPy](https://img.shields.io/badge/NumPy-1.26-blueviolet)
![Pandas](https://img.shields.io/badge/Pandas-2.0-purple)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-teal)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow)
![XGBoost](https://img.shields.io/badge/XGBoost-Optimized-green)
![TensorFlow](https://img.shields.io/badge/TensorFlow-ANN-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🎯 Objective  
- Build an accurate classification model for early-stage heart disease detection  
- Compare classical ML techniques vs. Deep Learning  
- Improve model transparency using SHAP explainability  
- Deploy a user-friendly web app for live prediction  
- Provide meaningful insights for clinical decision support  

---

## 📂 Dataset Summary  

The dataset includes essential cardiac & medical features commonly used in diagnosis.

| Feature Type | Examples |
|--------------|----------|
| ❤️ Cardiac Measures | Chest pain (cp), BP, MaxHR, Oldpeak |
| 🧬 Medical Attributes | Cholesterol, Fasting blood sugar, Exercise angina |
| 🧑‍⚕️ ECG Data | Rest ECG results, Slope, Thal |
| 🎯 Target Label | Heart disease (0/1) |

Total Features: **13**

---

## 🚀 Project Highlights
- Full ML pipeline: **EDA → Encoding → Scaling → Train/Val/Test Split → Model Comparison → ANN Training**
- Trained multiple classical ML models:
  - **Logistic Regression, KNN, Random Forest, XGBoost**
- Built a Deep Learning **ANN** with Batch Normalization, Dropout & EarlyStopping
- ANN achieved **94.2% accuracy** and **0.944 ROC-AUC**
- Integrated **SHAP Explainable AI** for global + local interpretability  
- Streamlit UI for real-time prediction & lifestyle recommendations

---

## ⚙️ Tech Stack and Libraries  

### 🧩 Programming Language  
- **Python 3.12+**

### 🧮 Core Libraries  
- NumPy — numerical computations  
- Pandas — data cleaning & preprocessing  
- Matplotlib, Seaborn — EDA & visualization  

### 🤖 Machine Learning  
- Scikit-Learn — preprocessing + baseline models  
- Logistic Regression  
- KNN  
- Random Forest  
- XGBoost  

### 🧠 Deep Learning  
- TensorFlow / Keras  
- ANN with:
  - Dense layers  
  - BatchNormalization  
  - Dropout regularization  

### 🧠 Explainable AI  
- **SHAP** → feature importance, summary plots, force plots  

### 🚀 Deployment  
- Streamlit → interactive prediction web app  
- Pickle → model + scaler storage  
- VS Code / Colab → development environment  

---

## 📈 Model Performance (Classical ML)

| Model                | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|----------------------|----------|-----------|--------|----------|---------|
| Logistic Regression  | 0.917    | 1.000     | 0.821  | 0.902    | 0.911   |
| KNN                  | 0.900    | 1.000     | 0.786  | 0.880    | 0.893   |
| Random Forest        | 0.883    | 0.957     | 0.786  | 0.863    | 0.877   |
| XGBoost              | 0.850    | 0.880     | 0.786  | 0.830    | 0.846   |

---

## 🤖 Deep Learning (ANN) Results

- **Accuracy:** 0.850  
- **Precision:** 1.000  
- **Recall:** 0.679  
- **F1-score:** 0.809  
- **ROC-AUC:** 0.944  

---

## 🧠 Explainable AI (SHAP)

- SHAP Summary Plot (Global Importance)
- SHAP Force Plot (Per-patient explanation)
- Helps understand feature influence behind model decisions  
- Useful for transparency and healthcare ML adoption

---

### 🏫 **Project Context**
Developed as part of Machine Learning coursework + independent research focusing on predictive healthcare analytics.

---

### 💬 **Quote**
> *“Accurate disease prediction isn’t just a technical achievement — it’s a step toward early intervention, better decisions, and smarter healthcare.”*

---

### 👤 **Author**
**Safwaan Siddiqui**  
[GitHub Profile](https://github.com/safwaan-exe)
