# LAB # 03: Logistic Regression

## Objective
To understand the concept of Logistic Regression and implement Logistic Regression for binary classification.

---

## Lab Tasks Overview

### 1. Dataset Loading
* **Dataset:** Imported and loaded the **Breast Cancer Dataset** via `sklearn.datasets`.

### 2. Exploratory Data Analysis (EDA)
* **Data Inspection:** Displayed the first few rows of the dataset to understand its structure.
* **Missing Values:** Checked for any missing values within the dataset.
* **Feature Distribution:** Plotted histograms to observe the distribution of various features.
* **Class Distribution:** Analyzed the balance between the target classes (malignant vs. benign) using a count plot.

### 3. Data Preprocessing
* **Feature Separation:** Split the dataset into features ($X$) and labels ($y$).
* **Data Splitting:** Performed a train-test split to evaluate the model on unseen data.
* **Standardization:** Standardized the feature values using `StandardScaler` to ensure optimal model performance.

### 4. Model Implementation
* **Initialization:** Utilized `sklearn.linear_model.LogisticRegression` for the binary classification task.
* **Training:** Trained the model on the preprocessed training data.
* **Prediction:** Generated predictions using the test data.

### 5. Evaluation Metrics
The model's performance was evaluated using the following metrics:
* **Accuracy Score:** To measure the overall correctness of the model.
* **Confusion Matrix:** To visualize true positives, true negatives, false positives, and false negatives.
* **Classification Report:** To compute **Precision**, **Recall**, and **F1-score**.

---

## Requirements & Dependencies
* Python 3.x
* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`
* `scikit-learn`
