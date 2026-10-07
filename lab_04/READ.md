# LAB # 04: Decision Tree Classifier

## Objective
To understand and implement a Decision Tree Classifier for classification tasks[cite: 18].

---

## Lab Tasks Overview

### Task 1: Load Dataset
* **Dataset Selection:** Used the **Iris dataset** from `sklearn.datasets`[cite: 21].

### Task 2: Exploratory Data Analysis (EDA)
* **Dataset Inspection:** Displayed dataset information, shape, and statistical summary[cite: 21].
* **Feature Distributions:** Plotted feature distributions utilizing pairplots[cite: 21].
* **Correlation:** Visualized feature correlations using a heatmap[cite: 21].

### Task 3: Data Preprocessing
* **Train-Test Split:** Split the dataset into training and testing sets utilizing a 70% train and 30% test ratio[cite: 21].

### Task 4: Build Decision Tree Classifier
* **Model Training:** Initialized and trained the model using `DecisionTreeClassifier`[cite: 21].

### Task 5: Model Evaluation
* **Predictions:** Made predictions on the unseen test data[cite: 22].
* **Evaluation Metrics:** Evaluated the model utilizing[cite: 22]:
  * Accuracy Score[cite: 22]
  * Confusion Matrix[cite: 22]
  * Classification Report[cite: 22]

### Task 6: Experimentation
* **Parameter Tuning:** Changed model parameters, explicitly testing `criterion = "entropy"`, `max_depth`, and `min_samples_split`[cite: 22].
* **Model Comparison:** Compared the baseline Gini model against the Entropy experiment to observe the effects of constraints on overfitting versus underfitting[cite: 22]. By applying pruning parameters like `max_depth`, tree complexity is reduced to improve generalization[cite: 20, 22].

---

## Requirements & Dependencies
* Python 3.x
* `pandas`
* `matplotlib`
* `seaborn`
* `scikit-learn`
