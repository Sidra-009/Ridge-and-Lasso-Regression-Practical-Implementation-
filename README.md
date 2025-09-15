# 📊 Ridge and Lasso Regression – Practical Implementation

This project demonstrates the implementation of **Ridge** and **Lasso** regression models using the **California Housing Dataset**.  
It highlights how regularization techniques improve model performance by reducing overfitting and handling multicollinearity.

---

## 📂 Project Structure

- `ridge_lasso.ipynb` — Step-by-step Jupyter Notebook implementation  
- `README.md` — Project overview and instructions  

---

## 🚀 Features

- ✅ Load and explore the California housing dataset  
- ✅ Build Linear, Ridge, and Lasso regression models  
- ✅ Tune hyperparameters efficiently with `GridSearchCV`  
- ✅ Evaluate models using **R² Score** and **Mean Squared Error (MSE)**  
- ✅ Visualize residual errors with smooth KDE plots using Seaborn  

---

## 🛠️ Tools & Libraries

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- scikit-learn

---

## 📊 Model Comparison

| Model             | Regularization | Purpose                                           |
|-------------------|----------------|--------------------------------------------------|
| Linear Regression | None           | Baseline model                                   |
| Ridge Regression  | L2             | Shrinks coefficients to reduce overfitting     |
| Lasso Regression  | L1             | Shrinks coefficients and performs feature selection |

---

## 📈 Evaluation Metrics

- **R² Score** — Measures explained variance  
- **Mean Squared Error (MSE)** — Measures prediction error  
- **Residual Distribution Plots** — Visualize error spread  

---

## 🖥️ How to USE

1. **Clone this repository:**

```bash
git clone https://github.com/Sidra-009/ridge-lasso-regression.git
cd ridge-lasso-regression
