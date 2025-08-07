**# Ridge and Lasso Regression – Practical Implementation

This project demonstrates how to implement **Ridge** and **Lasso** regression models using the **California Housing Dataset**. It showcases regularization techniques that help improve model performance by preventing overfitting and managing multicollinearity.

---

## Project Structure

- `ridge_lasso.ipynb` – Jupyter Notebook with step-by-step implementation  
- `README.md` – Project overview and instructions  

---

## Features

- Load and explore the California housing dataset  
- Implement Linear, Ridge, and Lasso regression models  
- Perform hyperparameter tuning using `GridSearchCV`  
- Evaluate model performance using R² score and mean squared error  
- Visualize residuals through KDE plots using Seaborn  

---

## Tools and Libraries

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- scikit-learn  

---

## Model Comparison

| Model             | Regularization | Purpose                                          |
|-------------------|----------------|--------------------------------------------------|
| Linear Regression | None           | Baseline model                                   |
| Ridge Regression  | L2             | Shrinks coefficients to reduce overfitting     |
| Lasso Regression  | L1             | Shrinks coefficients and performs feature selection |

---

## Evaluation Metrics

- R² Score  
- Mean Squared Error (MSE)  
- Residual distribution plots  

