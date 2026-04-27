# 💳 Credit Card Fraud Detection (Task 2)

This project is part of my Machine Learning Internship at CodSoft.

---

## 🎯 Objective

To build a machine learning model that detects **fraudulent credit card transactions**.

---

## 📊 Dataset

* **0 → Legitimate**
* **1 → Fraudulent**

⚠️ Highly imbalanced dataset.

---

## 🧪 Steps Performed

* Data Cleaning
* Feature Selection
* Handling Imbalanced Data
* Train-Test Split
* Model Training & Evaluation

---

## 🤖 Models Used

* Logistic Regression
* Random Forest
* Decision Tree

---

## 📊 Model Comparison

| Model               | Accuracy | Recall (Fraud) |
| ------------------- | -------- | -------------- |
| Logistic Regression | ~96%     | **High**       |
| Random Forest       | ~99%     | Low            |
| Decision Tree       | ~99%     | Moderate       |

---

## 🏆 Final Model

**Logistic Regression** (best recall for fraud detection)

---

## 🧠 Key Insights

* Accuracy is misleading for imbalanced data
* Recall is the most important metric
* Logistic Regression performs better for detecting fraud

---

## 🛠️ Tech Stack

Python, Pandas, Scikit-learn, Jupyter

---

## 📦 Usage

```bash id="fraud_run"
jupyter notebook
```

---

## ⚠️ Limitations

* False positives possible
* Depends on dataset quality

---

## 👩‍💻 Author

Sushma R
