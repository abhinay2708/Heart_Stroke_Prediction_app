# ❤️ Heart Stroke Prediction App

This is a simple machine learning web application built using **Streamlit** that predicts the likelihood of a person having a **stroke** based on health-related features.

---

## 🚀 Features

- Takes user input for features like age, gender, hypertension, heart disease, etc.
- Uses a trained machine learning model to make predictions.
- Built with Streamlit for quick and easy web deployment.
- Clean and user-friendly interface.

---

## 🧠 Machine Learning

- Trained using **scikit-learn** models (e.g., Logistic Regression, Random Forest, etc.)
- Preprocessing includes:
  - Handling missing values
  - Feature scaling using `StandardScaler`
  - Encoding categorical variables using one-hot encoding
- Model serialized using `joblib`

---

## 📦 Requirements

Install the dependencies using:

```bash
pip install -r requirements.txt
