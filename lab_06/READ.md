# LAB # 06: Support Vector Machine (SVM) Classifier

## Objective
To understand the Support Vector Machine (SVM) Classifier algorithm and implement an SVM classifier for binary classification[cite: 27].

## Theory Highlights
Support Vector Machines (SVM) are heavily utilized for classification due to their distinct ability to handle high-dimensional data and small sample sizes[cite: 27]. 
* **How it Works:** SVM searches for the optimal hyperplane that maximizes the margin separating two distinct classes[cite: 28]. The data points that establish this margin boundary are known as **support vectors**[cite: 28].
* **Soft Margin & C Parameter:** A strict separation is a *Hard Margin*, whereas a *Soft Margin* permits some misclassifications, which is regulated by the regularization parameter **C**[cite: 28].
* **The Kernel Trick:** If data is not linearly separable, kernel functions transform the data into a higher-dimensional space where it can be separated[cite: 28]. Common formulas include[cite: 28]:
  * **Linear Kernel:** $K(x_i, x_j) = x_i^T x_j$
  * **Polynomial Kernel:** $K(x_i, x_j) = (x_i^T x_j + c)^d$
  * **Radial Basis Function (RBF) Kernel:** $K(x_i, x_j) = \exp(-\gamma \vert{}\vert{}x_i - x_j\vert{}\vert{}^2)$

---

## Lab Tasks Overview

### Task 1: Load Dataset
* **Dataset Selection:** Loaded the **Breast Cancer dataset** via `sklearn.datasets` to serve as our binary classification dataset[cite: 29].

### Task 2: Data Preprocessing
* **Preprocessing Application:** Handled required numerical scaling using `StandardScaler` to ensure the SVM operates accurately within the feature space[cite: 29].

### Task 3: Train-Test Split
* **Data Splitting:** Divided the dataset into training and testing sets utilizing an 80/20 split ratio[cite: 29].

### Task 4 & 5: Grid Search & Predictions
* **Hyperparameter Tuning:** Applied Grid Search (`GridSearchCV`) to scan multiple parameters (`C`, `kernel`, `gamma`) and discover the optimal setup[cite: 29].
* **Test Predictions:** Utilized the best-found parameters to execute predictions on the isolated test set[cite: 29].

### Task 6: Performance Evaluation
Evaluated the final model's performance computing the following classification metrics[cite: 29]:
* **Accuracy Score**[cite: 29]
* **Precision**[cite: 29]
* **Recall**[cite: 29]
* **F1-Score**[cite: 29]

### Task 7: Confusion Matrix Visualization
* **Visualization:** Rendered a Seaborn heatmap to visually display the Confusion Matrix, tracking all correct and incorrect classifications[cite: 29].

---

## Requirements & Dependencies
* Python 3.x
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
