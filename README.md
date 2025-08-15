# Parkinson-s-Disease-Prediction-ML

## 📌 Overview
This project uses machine learning to predict whether a person has Parkinson's Disease based on biomedical voice measurements.  
The dataset contains various vocal features such as jitter, shimmer, and fundamental frequency parameters.

---

## 📂 Dataset
- **Source:** [UCI Machine Learning Repository - Parkinson's Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)
- **Target Variable:** `status`  
  - `1` → Parkinson's positive  
  - `0` → Healthy  
- **Rows:** 195  
- **Columns:** 24 (excluding `name`)

---

## ⚙️ Preprocessing
1. **Data Cleaning:** Removed unnecessary columns (`name`).
2. **Feature & Target Split:**
   ```python
   X = data.drop(columns=['name', 'status'], axis=1)
   y = data['status']



----
📌 Future Improvements

Use deep learning models for better accuracy.

Deploy as a web application using Flask/Streamlit.

Add cross-validation and hyperparameter tuning.

---
📜 License

This project is licensed under the MIT License


---- 
Author 

SANIYA CHHABRA
