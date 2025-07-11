# 💧 Water Pollutants Prediction Web App

This project is a **Machine Learning + Web App solution** that predicts the **concentration of six key water pollutants** (O₂, NO₃, NO₂, SO₄, PO₄, and CL) for river monitoring stations in **Ukraine** based on **historical water quality data (2000–2021)**. It uses **Random Forest Regression** for modeling and **Streamlit** for deployment as a user-friendly web interface.

---

## 📌 Why I Chose This Project

I chose this project because **water quality** is a vital concern in environmental science, public health, and sustainable development. Understanding how pollution levels may change over time can help:
- Environmental agencies monitor water safety
- Predict future contamination risks
- Plan timely intervention at high-risk stations

Also, this project gave me the opportunity to explore **real-world environmental datasets**, apply **machine learning**, and **build a complete data science pipeline** from raw data to a deployed model.

---

## 🚀 What the Project Does

### 🔹 Inputs:
- **Year** (e.g., 2024)
- **Station ID** (e.g., 1–22)

### 🔹 Outputs:
- Predicted pollutant levels for that station and year:
  - Dissolved Oxygen (O₂)
  - Nitrates (NO₃)
  - Nitrites (NO₂)
  - Sulphates (SO₄)
  - Phosphates (PO₄)
  - Chlorides (CL)

### 🔹 Technologies Used:
- `pandas`, `numpy` for data handling
- `RandomForestRegressor` inside `MultiOutputRegressor` to predict multiple pollutants simultaneously
- `joblib` to save/load the model
- `Streamlit` for creating a user interface

---

## 📚 What I Learned from This Project

Through this project, I gained hands-on experience with:

✅ Handling real-world data with missing values  
✅ Encoding categorical features using OneHotEncoding  
✅ Training and evaluating a **multi-output regression** model  
✅ Understanding **correlation between pollutants** through heatmaps  
✅ Saving and deploying models using `joblib`  
✅ Building and deploying a machine learning app using **Streamlit**  
✅ Making my machine learning project **interactive and user-friendly**

---

## 📷 Sample Prediction

For example, predicting pollutant levels at Station ID **22** in the year **2024** might return:

