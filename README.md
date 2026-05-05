# 🌱 AI-Based Crop Recommendation System

## 📌 Problem Statement

Farmers often face difficulty in deciding which crop to grow due to variations in soil nutrients and environmental conditions. Choosing the wrong crop can lead to low yield, financial loss, and inefficient use of resources.

This project aims to solve this problem by using machine learning to recommend the most suitable crop based on soil composition and climate factors.

---

## 🎯 Objective

To build a machine learning system that analyzes soil nutrients (N, P, K) and environmental conditions (temperature, humidity, pH, rainfall) to suggest the optimal crop for cultivation.

---

## 💡 Why This Project Matters

* Helps farmers make **data-driven decisions**
* Reduces risk of crop failure
* Improves agricultural productivity
* Demonstrates real-world application of ML in agriculture

---

## 🚀 Features

* Takes real-time user input for soil and weather conditions
* Predicts best crop using trained ML models
* Compares multiple models:

  * Logistic Regression
  * Decision Tree
  * Random Forest
* Selects best model based on performance metrics
* Outputs final recommended crop

---

## 🧠 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 📊 Dataset

Crop Recommendation Dataset (Kaggle)

### Features:

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature
* Humidity
* pH
* Rainfall

### Target:

* Crop label

---

## ⚙️ Methodology

1. Data Loading and Cleaning
2. Exploratory Data Analysis
3. Feature and Target Separation
4. Train-Test Split
5. Model Training:

   * Logistic Regression
   * Decision Tree
   * Random Forest
6. Model Evaluation using Accuracy & F1-score
7. Selection of Best Model
8. Prediction System using user input

---

## ▶️ How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
python your_script_name.py
```

---

## 🎯 Example Output

```
Recommended Crop: Rice
```

---

## 🔮 Future Improvements

* Build interactive UI using Streamlit
* Add fertilizer recommendation system
* Integrate weather API for real-time predictions
* Deploy as a web application

---

## 👩‍💻 Author

**Rupali Pasa**
