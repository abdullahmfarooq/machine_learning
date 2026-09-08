# Lab 01: Titanic Dataset Preprocessing

This folder contains the tasks completed for Lab 01, focusing on data cleaning, categorical encoding, feature scaling, and dataset splitting.

## Tasks Included
1. **Dataset Cleaning**: Handled missing values in `Age` using mean imputation and removed rows with missing `Embarked` values.
2. **Encoding Categorical Data**: 
   - Applied **Label Encoding** to convert `Sex` into numerical format.
   - Applied **One-Hot Encoding** to `Embarked` categories.
3. **Feature Scaling & Splitting**:
   - Selected features: `Age`, `Fare`, `Sex`, and `Pclass`.
   - Scaled features using `StandardScaler`.
   - Split dataset into **80% Training** and **20% Testing** sets.

## Files
- `lab_01.ipynb`: Jupyter Notebook containing the full code implementation.
- `train (1).csv`: Titanic dataset file used for the lab tasks.
