# 🔥 Forest Fire Prediction using Machine Learning

This project predicts the likelihood and severity of forest fires using environmental and meteorological data. It leverages machine learning models to classify fire events as **No Fire**, **Small Fire**, or **Large Fire**, helping authorities act before a disaster escalates.

---

## 📌 Problem Statement

Traditional systems detect fires **after they start**, relying on satellite or aerial surveillance. This project shifts the approach to **prediction**, using environmental data like temperature, humidity, wind speed, rainfall, and fire indices.

---

## 🎯 Objectives

- Predict fire occurrence and classify severity
- Automate predictions using a trained ML model
- Enable integration into dashboards, mobile/web apps, or edge devices
- Achieve at least 98% prediction accuracy

---

## 🧠 Machine Learning Models Used

- ✅ **Logistic Regression**
- ✅ **Support Vector Machine (RBF)**
- ✅ **Random Forest Classifier**
- ✅ **AdaBoost Classifier**
- ✅ **Multilayer Perceptron (Best Model)**

---

## 🧪 Dataset Details

- 📍 **Source**: UCI Machine Learning Repository
- 🌍 **Location**: Montesinho Natural Park, Portugal
- 🧾 **Records**: 517
- 📊 **Features**:
  - Temperature, Relative Humidity, Wind, Rain
  - FFMC, DMC, DC, ISI fire indices
  - Date: Month & Day
  - Area burned (used to classify `fire_scale`)

---

## 🔧 Labeling Strategy

A new categorical target `fire_scale` was created:

- `no_fire` → area = 0
- `small_fire` → 0 < area < 2 ha
- `large_fire` → area ≥ 2 ha

---

## 📈 Results Summary

| Model               | Test Accuracy |
|---------------------|---------------|
| Logistic Regression | ~98.0%        |
| SVM (RBF Kernel)    | ~98.0%        |
| Random Forest       | 98.0%         |
| AdaBoost            | 98.0%         |
| **MLP (Best)**      | **98.0%**     |

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`
- **Environment**: Jupyter Notebook / VS Code
- **Deployment-ready for**: Streamlit, Flask, or edge devices



