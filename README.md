# 🫀 Heart Disease Prediction AI Project

> Machine Learning-based Heart Disease Prediction using Patient Health Data

---

## 📌 Overview

This project aims to predict heart disease using machine learning models based on patient health data.
By analyzing health indicators such as age, blood pressure, cholesterol, and chest pain type, the model classifies whether a patient has heart disease or not.

---

## 🎯 Project Goals

* Analyze heart disease-related health data
* Perform data preprocessing and scaling
* Train machine learning classification models
* Compare model performance
* Interpret prediction results

---

## 🛠 Tech Stack

| Category         | Technologies        |
| ---------------- | ------------------- |
| Language         | Python              |
| Data Analysis    | Pandas, NumPy       |
| Visualization    | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn        |
| Environment      | Jupyter Notebook    |
| Version Control  | GitHub              |

---

## 📊 Dataset

### Heart Disease Cleveland Dataset

* Target: `condition`
* Class 0: Normal
* Class 1: Heart Disease

| Feature   | Description          |
| --------- | -------------------- |
| age       | Age                  |
| sex       | Sex                  |
| cp        | Chest pain type      |
| chol      | Cholesterol          |
| condition | Heart disease status |

---

## 🧹 Data Preprocessing

* Checked dataset information
* Split feature / target data
* Applied train/test split (8:2)
* Used StandardScaler

---

## 🤖 Machine Learning Models

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 0.92     |
| SVM                 | 0.90     |
| Random Forest       | 0.88     |

> Logistic Regression showed the best performance.

---

## 🏆 Best Model

### Logistic Regression

### Reason

* Highest Accuracy
* Stable prediction performance
* Easy to interpret compared to complex models

---

## 📌 Confusion Matrix

```text
[[32  0]
 [ 5 23]]
```

| Actual / Predicted | 0 (Normal) | 1 (Heart Disease) |
| ------------------ | ---------- | ----------------- |
| 0 (Normal)         | 32         | 0                 |
| 1 (Heart Disease)  | 5          | 23                |

### Interpretation

* Correctly predicted all normal patients
* Correctly identified 23 heart disease patients
* 5 heart disease patients were incorrectly predicted as normal

> In medical AI, reducing False Negative cases is important because missing actual patients can be risky.

---

## 📈 Key Insights

* Logistic Regression achieved the highest accuracy
* Precision was very high, indicating reliable positive predictions
* Recall needs improvement because some actual heart disease patients were missed
* Medical AI should consider Recall as well as Accuracy

---

## 🚀 Conclusion

This project implemented a machine learning-based heart disease prediction model using patient health data.
Among the tested models, Logistic Regression achieved the best performance.
However, some heart disease patients were incorrectly classified as normal, so future improvements should focus on improving Recall.

---