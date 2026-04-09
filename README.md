# ❤️ Heart Stroke Predictor

A machine learning-powered web application that predicts the likelihood of heart stroke based on user health parameters. This project combines data science and an interactive interface to assist in early risk assessment.

---

## 🚀 Features

* 🧠 Predicts heart stroke risk using a trained ML model
* 📊 Uses real-world health parameters for accurate predictions
* ⚡ Fast and responsive interface
* 🧩 Scaler + trained KNN model integration
* 🖥️ Simple Python-based deployment

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit / Python UI
* **Backend:** Python
* **ML Model:** K-Nearest Neighbors (KNN)
* **Libraries:**

  * scikit-learn
  * pandas
  * numpy
  * joblib

---

## 📂 Project Structure

```bash
Heart/
│── app.py                  # Main application
│── HeartdiseaseFinal.ipynb # Model training notebook
│── knn_heart_model.pkl     # Trained ML model
│── heart_scaler.pkl        # Data scaler
│── heart_columns.pkl       # Feature columns
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/HRISHIKESH-hackoff/HeartStrokepredictor.git
cd Heart
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the app

```bash
python app.py
```

---

## 🧪 How It Works

1. User inputs health data (age, cholesterol, BP, etc.)
2. Data is scaled using a pre-trained scaler
3. Model processes input using KNN algorithm
4. Prediction is displayed instantly

---

## 📊 Model Details

* Algorithm: **K-Nearest Neighbors (KNN)**
* Preprocessing: StandardScaler
* Training done using real-world dataset
* Outputs binary classification (Risk / No Risk)

---

## ⚠️ Disclaimer

This project is for **educational purposes only** and should not be used as a substitute for professional medical advice.

---

## 📌 Future Improvements

* 🌐 Deploy as a web app (Streamlit Cloud / Render)
* 📈 Improve model accuracy with advanced algorithms
* 📊 Add visualization dashboards
* 🔐 Add user authentication

---

## 🙌 Acknowledgment

Inspired by existing machine learning implementations and enhanced with custom modifications.

---

## 👨‍💻 Author

**Hrishikesh Mandal**
GitHub: [https://github.com/HRISHIKESH-hackoff](https://github.com/HRISHIKESH-hackoff)

---

# ⭐ If you like this project, give it a star!

---

