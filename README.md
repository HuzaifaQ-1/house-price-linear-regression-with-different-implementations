#  House Price Prediction using Linear Regression

##  Overview

This project explores different implementations of **Linear Regression** for predicting house prices using a real dataset.

The goal is to:

* Understand linear regression deeply (including from-scratch implementation)
* Compare performance across different approaches
* Analyze the effect of feature selection and model complexity

---

##  Models Implemented

* 🔹 Single Feature Linear Regression
* 🔹 Multiple Feature Linear Regression
* 🔹 Polynomial Regression
* 🔹 Linear Regression (from scratch using NumPy)
* 🔹 Feature Selection (Top-K features)

---

##  Model Comparison Summary

### 1. Single Feature Linear Regression (Area)

* **R² Score:** 0.27
* **RMSE:** ~1,917,103
* ❗ Insight: Area alone is not enough for accurate prediction.

---

### 2. Linear Regression (All Features)

* **R² Score:** 0.65
* **RMSE:** ~1,324,507
*  Insight: Best performance — more features improve predictions significantly.

---

### 3. Polynomial Regression

* **R² Score:** ~0.62
* **RMSE:** ~1,383,570
*  Insight: No major improvement — relationships are mostly linear.

---

### 4. Linear Regression (From Scratch)

* **R² Score:** ~0.65
* **RMSE:** ~1,324,507
*  Insight: Matches sklearn implementation after proper scaling.

---

### 5. Feature Selection (Top-K Features)

* Top 1 → R²: 0.27
* Top 3 → R²: 0.49
* Top 7 → R²: 0.61
* Top 13+ → R²: 0.65

**Insight:** Most performance gain comes from the first few important features.

---

##  Evaluation Metrics

* R² Score
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

##  Key Takeaways

* Single feature is insufficient for accurate predictions
* Multiple features significantly improve performance
* Diminishing returns after adding key features
* Linear regression is already strong for this dataset
* Feature scaling is critical for gradient descent
* Scratch implementation can match library models

---

##  Final Conclusion

Using multiple features provides the best prediction performance, while increasing model complexity beyond linear regression offers limited benefit.

---

##  Dataset

* `Housing.csv`

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 👤 Author
Muhammad Huzaifa Qazi

Huzaifa Qazi
