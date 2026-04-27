# 📉 Customer Churn Prediction (Task 3)

This project focuses on predicting whether a customer will leave a service based on historical data.

---

## 🎯 Objective

To build a model that identifies customers likely to churn.

---

## 📊 Dataset

* Target variable:

  * **0 → Stay**
  * **1 → Churn (Exited)**

---

## 🧪 Steps Performed

* Data Cleaning
* Feature Selection
* Encoding Categorical Variables
* Train-Test Split
* Model Training & Evaluation

---

## 🤖 Models Used

* Logistic Regression
* Random Forest
* Gradient Boosting

---

## 📊 Model Comparison

| Model               | Accuracy   |
| ------------------- | ---------- |
| Logistic Regression | ~81%       |
| Random Forest       | ~86.6%     |
| Gradient Boosting   | **~86.7%** |

---

## 🏆 Final Model

**Gradient Boosting** (best overall performance)

---

## 🧠 Key Insights

* Ensemble models perform better on structured data
* Gradient Boosting provided best balance of performance
* Model comparison helps in selecting optimal solution

---

## 🛠️ Tech Stack

Python, Pandas, Scikit-learn, Jupyter

---

## 📦 Usage

```bash id="churn_run"
jupyter notebook
```

---

## ⚠️ Limitations

* May not generalize to different datasets
* Performance depends on feature quality

---

## 👩‍💻 Author

Sushma R
