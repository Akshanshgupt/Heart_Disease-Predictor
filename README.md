# ❤️ Heart Disease Prediction App

A **Machine Learning–based Heart Disease Prediction web application** built using **Python** and **Streamlit**. This app takes medical parameters as input and predicts whether a person has a **high or low risk of heart disease** using a trained **K-Nearest Neighbors (KNN)** model.

---

## 🚀 Features

* Interactive **Streamlit web UI**
* Predicts heart disease risk in real time
* Uses a trained **KNN model**
* Input data is **scaled** before prediction
* Handles categorical features using one-hot encoding

---

## 🧠 Machine Learning Model

* **Algorithm:** K-Nearest Neighbors (KNN)
* **Preprocessing:** StandardScaler
* **Model Storage:** Joblib (`.pkl` files)

---

## 📂 Project Structure

```
Heart_Disease-Predictor/
│── app.py
│── requirements.txt
│── knn_heart_model.pkl
│── heart_scaler.pkl
│── heart_columns.pkl
│── README.md
```

---

## 🛠️ Tech Stack

* Python 🐍
* Streamlit 🎈
* Pandas
* NumPy
* Scikit-learn
* Joblib

---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Akshanshgupt/Heart_Disease-Predictor.git
cd Heart_Disease-Predictor
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App

```bash
streamlit run app.py
```

---

## 📊 Input Parameters

* Age
* Sex (M / F)
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol Level
* Fasting Blood Sugar
* Resting ECG
* Max Heart Rate
* Exercise-Induced Angina
* Oldpeak (ST Depression)
* ST Slope

---

## ✅ Output

* **Low Risk of Heart Disease**
* **High Risk of Heart Disease**

---

## ⚠️ Disclaimer

This project is for **educational purposes only** and should **not be used as a medical diagnosis tool**.

---

## 👤 Author

**Akshansh Gupta**

If you like this project, don’t forget to ⭐ the repository!
