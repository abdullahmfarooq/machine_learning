# LAB # 02: Simple and Multiple Linear Regression

## Objective
To understand and implement **Simple Linear Regression** and **Multiple Linear Regression** using Python and `scikit-learn`.

---

## Lab Tasks Overview

### Task 1: Simple Linear Regression
* **Dataset:** Loaded the Diabetes dataset from `sklearn.datasets`[cite: 5].
* **Feature Selection:** Selected a single independent variable (`bmi`) to predict the target variable (`disease progression`)[cite: 5].
* **Exploratory Data Analysis (EDA):** Generated scatter plots and analyzed correlation values between BMI and disease progression[cite: 5].
* **Model Implementation:** Split data into training/testing sets, fitted a `LinearRegression` model, and plotted the resulting regression line[cite: 5, 6].
* **Evaluation Metrics:** Evaluated performance using **Mean Squared Error (MSE)** and **R² Score**[cite: 6].

### Task 2: Multivariate Linear Regression
* **Dataset:** Utilized all 10 independent features from the Diabetes dataset[cite: 7].
* **Exploratory Data Analysis (EDA):** Generated a correlation heatmap and pair plots for key features[cite: 7, 8].
* **Model Implementation:** Trained a multiple linear regression model utilizing all features simultaneously[cite: 8].
* **Visualizations:** Created actual vs. predicted scatter plots and residual plots to analyze errors[cite: 8].
* **Evaluation Metrics:** Evaluated model performance using **MSE**, **RMSE**, and **R² Score**[cite: 8].

### Task 3: Experimentation & Comparison
* Compared the evaluation metrics of Simple Linear Regression versus Multivariate Linear Regression to observe how incorporating more features improves predictive accuracy[cite: 8].

---

## Evaluation Summary

| Model | MSE | RMSE | R² Score |
| :--- | :--- | :--- | :--- |
| **Simple Linear Regression (`bmi`)** | Higher | Higher | Lower (~0.23 - 0.35) |
| **Multivariate Linear Regression (All Features)** | Lower | Lower | Higher (~0.45 - 0.50) |

---

## Requirements & Dependencies
* Python 3.x
* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`
* `scikit-learn`
