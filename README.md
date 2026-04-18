# 🛰️ AI-Based Urban Expansion & Commercial Activity Analysis

A machine learning project that analyzes **urban growth and commercial activity** using satellite imagery and advanced AI models.  
The project aims to support **smart city planning** by providing accurate, data-driven insights about land use and urban development.

---

## ✨ Features

- Analyze urban expansion using satellite data  
- Detect commercial activity hotspots  
- Apply Machine Learning & Deep Learning models  
- Advanced feature engineering (spatial & temporal)  
- Model comparison (XGBoost vs LightGBM)  
- Hyperparameter tuning using Optuna  
- High accuracy with minimal overfitting  

---

## 🛠 Technologies Used

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **Models:** XGBoost, LightGBM  
- **Optimization:** Optuna  
- **Visualization:** Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook / Google Colab  

---

## 🧹 Data Preprocessing

Data preprocessing was applied to prepare satellite and geospatial data for modeling.

### Steps Performed

- Handling missing values  
- Feature scaling (Normalization / Standardization)  
- Encoding categorical variables (One-hot encoding)  
- Feature engineering:
  - Latitude & Longitude  
  - Distance to city center  
  - Time features (month, year, seasonal encoding)  
  - Spectral indices (NDVI, NDBI, IBI, etc.)  

📸 **Screenshots to add:**
- Dataset before & after preprocessing  
- Feature engineering output  

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was performed to understand patterns in urban expansion.

### Analysis Performed

- Feature distributions  
- Correlation analysis  
- Spatial & temporal relationships  
- Urban vs non-urban patterns  

📸 **Screenshots to add:**
- Histogram plots  
- Correlation heatmap  

---

## 🤖 Machine Learning Models

### 1. XGBoost
- Strong baseline model  
- Good generalization performance  

### 2. LightGBM
- High efficiency and speed  
- Excellent performance on structured data  

### 3. Optuna-Tuned LightGBM ⭐
- Best performing model  
- Optimized hyperparameters  
- Highest accuracy and stability  

---

## ⚙️ Model Training

- Train/Test Split: **80% / 20%**  
- Stratified sampling to preserve class balance  

### Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  



---

## 📊 Model Evaluation

### Confusion Matrix

Shows classification performance across classes.


![LightGBM Confusion Matrix](images/lightgbm_confusion_matrix.png)
![XGBoost Confusion Matrix](images/xgboost_confusion_matrix.png)
---

### ROC Curve

Compares model performance.


![ROC Curve](images/roc_curve.png)
---


---

## 💡 Key Insights

- LightGBM outperformed XGBoost  
- Optuna significantly improved performance  
- Very low overfitting (~0.6% difference)  
- Satellite features effectively capture urban growth  
- Accurate classification of:
  - Built-up areas  
  - Non-built areas  
  - Commercial zones  

---

## 📊 Results Summary

| Model                | Accuracy |
|---------------------|---------|
| XGBoost             | ~95%    |
| LightGBM            | ~98.7%  |
| Tuned LightGBM      | **~99.1%** |

- ROC-AUC ≈ **1.000 (near perfect)**  

---

## 🎯 Project Purpose

- Apply Machine Learning on real-world geospatial data  
- Understand urban expansion patterns  
- Practice feature engineering  
- Learn model optimization techniques  
- Support smart city planning  

---

## 🚀 Try It

Run the project using:

- Jupyter Notebook  
- Google Colab  

🔗 **Open in Colab:** 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ETFVsRSJPAfGob540-CZjyEVIFXsXg1f?hl=ar-SY)
---

---

## 👥 Team Members
- Jenan Hatim Bajawi  
- Linda Hussai Alzahrani  
- Raghad Ahmad Alzahrani  
- Salam Ali Alghamdi  
- Khadija Ali Mirza  

---

## 📌 Notes

- Based on satellite imagery data  
- Uses Machine Learning & Deep Learning  
- Suitable for smart city applications  
- Can be extended using advanced deep learning models (CNN-LSTM)  

---

## ⭐ Future Work

- Apply CNN/LSTM for spatiotemporal prediction  
- Use higher-resolution satellite images  
- Expand to multiple cities  
- Real-time monitoring system  

---
