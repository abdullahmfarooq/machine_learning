# LAB # 08: KNN Classifier

## Objective
To understand the K-Nearest Neighbors (KNN) Classifier algorithm and implement KNN for classification tasks[cite: 33].

## Theory Highlights
* **Lazy Learning:** KNN is a lazy learning algorithm, meaning it does not build a generalized explicit model during training; instead, it memorizes/stores the training data and performs classification on new data points dynamically based on distance metrics[cite: 34].
* **Distance Metrics:** Distances are computed using methods such as[cite: 34]:
  * **Euclidean Distance:** $d(x, y) = \sqrt{\sum (x_i - y_i)^2}$[cite: 34]
  * **Manhattan Distance:** $d(x, y) = \sum |x_i - y_i|$[cite: 34]
* **Choosing the Value of K:** 
  * *Small K:* Highly sensitive to noise and prone to overfitting[cite: 34].
  * *Large K:* Yields a smoother decision boundary, but may underfit[cite: 34].
  * *Optimal K:* Typically selected using cross-validation[cite: 34].
* **Prediction Rule:** Assigns the class label by finding the statistical mode among the $K$ nearest neighbors ($\hat{y} = \text{mode}(\{y_i | x_i \text{ is among the K nearest neighbors}\})$)[cite: 35].

---

## Lab Tasks Overview

### Task 1: Load Dataset
* **Dataset Selection:** Loaded the **Breast Cancer Dataset** via `sklearn.datasets`[cite: 35].

### Task 2: Data Preprocessing
* **Data Inspection & Handling:** Checked for missing values and prepared feature arrays and class labels for training[cite: 35].

### Task 3: Train-Test Split
* **Data Partitioning:** Split the dataset into training and testing sets, followed by numerical feature scaling using `StandardScaler`[cite: 35].

### Task 4 & 5: Train KNN and Make Predictions
* **Multiple K Execution:** Instantiated and trained `KNeighborsClassifier` across multiple values of $K$ ($3, 5, 7$) to generate test set predictions[cite: 35].

### Task 6: Evaluate Performance
* **Metrics:** Computed accuracy, precision, recall, and F1-score alongside rendering a Confusion Matrix heatmap[cite: 35].

### Task 7: Test Accuracy Changes Across K
* **Comparative Analysis:** Evaluated how changes in the parameter $K$ impact overall prediction accuracy[cite: 35].

---

## Requirements & Dependencies
* Python 3.x
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
