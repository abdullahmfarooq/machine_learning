# LAB # 05: Random Forest Classifier

## Objective
To understand and implement a Random Forest Classifier for classification tasks[cite: 23].

---

## Lab Tasks Overview

### Task 1: Load Dataset
* **Dataset Selection:** Loaded the **Titanic dataset** via `seaborn.load_dataset('titanic')`[cite: 25].

### Task 2: Data Preprocessing
* **Missing Value Handling:** Imputed missing values in numerical columns (e.g., `age` using median) and categorical columns (e.g., `embarked` using mode)[cite: 25].
* **Categorical Encoding:** Encoded categorical predictors using one-hot encoding (`pd.get_dummies`)[cite: 25].

### Task 3: Train-Test Split
* **Data Splitting:** Partitioned the dataset into an 80% training set and a 20% testing set using `train_test_split`[cite: 25].

### Task 4 & 5: Model Implementation & Predictions
* **Model Training:** Initialized and trained `RandomForestClassifier` with 100 decision trees (`n_estimators=100`)[cite: 24, 25].
* **Predictions:** Generated classification predictions on the unseen test dataset[cite: 25].

### Task 6: Performance Evaluation
Evaluated performance using the following classification metrics[cite: 25]:
* **Accuracy Score**[cite: 25]
* **Precision**[cite: 25]
* **Recall**[cite: 25]
* **F1-Score**[cite: 25]

### Task 7: Confusion Matrix Visualization
* **Heatmap Plotting:** Visualized true positive, true negative, false positive, and false negative counts using `seaborn.heatmap`[cite: 25].

### Task 8: Comparison with Single Decision Tree
* **Model Comparison:** Evaluated performance differences between a single `DecisionTreeClassifier` and `RandomForestClassifier`[cite: 25].
* **Observation:** The Random Forest model achieved better generalization and robustness due to ensemble averaging (bagging) and feature randomness, mitigating individual decision tree overfitting[cite: 23, 24].

---

## Requirements & Dependencies
* Python 3.x
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
