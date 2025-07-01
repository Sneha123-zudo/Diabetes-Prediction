# 🩺 Diabetes Prediction App

A simple and interactive **Machine Learning web application** built using **Streamlit** that predicts whether a person is likely to have **diabetes** based on various medical attributes. This app uses a pre-trained **Random Forest Classifier** and provides instant results through a clean and user-friendly interface.

---

## 🌟 Features

- 🔍 Predicts the likelihood of diabetes using health metrics.
- 🧠 Uses a trained **Random Forest model**.
- 🌐 Built with **Streamlit** — works directly in the browser.
- 📊 (Optional) SHAP integration for explainability of predictions.
- ✅ Easy to run locally or deploy online.

---

## 📸 Demo

🔗 **Live App**: [Click here to try the Diabetes Prediction App](https://your-app-name.streamlit.app)

> Replace the above link with your actual Streamlit app URL after deployment.

---

## ⚙️ How It Works

1. The app loads a machine learning model (`diabetes_model.pkl`) trained on a dataset like the **PIMA Indian Diabetes Dataset**.
2. The user provides medical inputs like:
   - Glucose level
   - Blood pressure
   - BMI
   - Age
   - Insulin, and more.
3. The model processes the input and returns:
   - ✅ **0 – Not Diabetic**
   - ❌ **1 – Diabetic**
4. (Optional) SHAP is used to explain the influence of each feature.

---

## 🛠️ Tech Stack

| Technology      | Description                          |
|------------------|--------------------------------------|
| **Python**       | Core programming language            |
| **Streamlit**    | For creating the web interface       |
| **scikit-learn** | For ML model training and inference  |
| **SHAP**         | For model interpretability (optional)|
| **pandas / numpy** | For data manipulation              |
| **matplotlib / seaborn** | For visualization             |

---

## Run the app
streamlit run app.py

