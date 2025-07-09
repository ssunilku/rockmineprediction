# 🪨 Rock vs Mine Prediction using Machine Learning

This project is a binary classification system that predicts whether an object detected by sonar is a **rock** or a **mine** based on sonar signal data.

---

## 📌 Project Overview

- Developed a machine learning model using the **UCI Sonar dataset**
- The system is trained on numerical attributes of sonar signals
- It classifies objects as **Rock** (R) or **Mine** (M)
- Implemented using **Python** and **Scikit-learn**

---

## 🧠 Algorithms Used

- **Logistic Regression** (primary model)
- Accuracy tested on both training and test datasets

---

## 🔧 Technologies & Libraries

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 📊 Dataset

- Source: [UCI Machine Learning Repository - Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- 208 instances, 60 features each
- Output labels: `R` (Rock) or `M` (Mine)

---

## 🧪 How It Works

1. Load the dataset and explore the data
2. Split into training and testing sets
3. Train Logistic Regression model
4. Evaluate model accuracy
5. Make predictions on custom input data

---

## ✅ Sample Prediction

```python
input_data = (0.02, 0.03, ..., 0.15)  # 60 features
# Model returns: "Mine" or "Rock"
