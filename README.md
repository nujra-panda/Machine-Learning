# California Housing Price Prediction using Linear Regression

This project builds a simple **Linear Regression** model from scratch (using NumPy) to predict California housing prices. It uses the publicly available `housing.csv` dataset and demonstrates key machine learning workflow steps, including data preprocessing, normalization, model fitting, and evaluation using Mean Squared Error (MSE) and R² score.

---

## Files

- `Untitled.ipynb`: Main Jupyter notebook implementing linear regression using the normal equation.
- `housing.csv`: Dataset used for training/testing (not included here—please add your own copy).

---

## Features

- Data cleaning & one-hot encoding for categorical variables
- Feature scaling using `StandardScaler`
- Linear regression using **normal equations** (no sklearn models)
- Evaluation using:
  - Mean Squared Error (MSE)
  - R² score (accuracy)
- Visualization: Actual vs Predicted house prices plot

---

## How to Run

1. Clone this repository or download the notebook.
2. Place `housing.csv` in the same directory as the notebook.
3. Install required packages:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
4. Open `Untitled.ipynb` in Jupyter Notebook or VSCode.
5. Run all cells to see predictions and evaluation.

---

## Example Output

```
Mean Squared Error (MSE): 4826178963.51
R² Score (Accuracy): 64.82%
```

> Accuracy and error will vary based on data and random train-test split.

---

## Concepts Used

- Linear regression via **normal equation**:  
  `$\theta = (X^TX)^{-1}X^Ty$`
- Standardization of features  
- Train/Test Split
- Evaluation metrics: MSE & R²

---

## Notes

- This is a **from-scratch** implementation using matrix algebra.
- Does **not** use `LinearRegression` from scikit-learn to reinforce understanding of fundamentals.
