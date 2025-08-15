# Task 7: Support Vector Machines (SVM) – Breast Cancer Dataset

Hi!! This repository contains my implementation of classification using Support Vector Machines (SVM), applied to the Breast Cancer Wisconsin dataset.  
The goal was to train, evaluate, and tune SVM models with different kernels to predict whether a tumor is benign (0) or malignant (1).

---

## What This Task Covers

- Import and preprocess the dataset  
- Encode categorical variables and target column  
- Remove unnecessary columns (if present)  
- Handle missing values and ensure all inputs are numeric  
- Normalize features using `StandardScaler`  
- Train SVM models with:
  - Linear kernel
  - RBF kernel
- Perform hyperparameter tuning using `GridSearchCV`  
- Evaluate models using:
  - Accuracy
  - Classification report
  - Confusion matrix
- Perform cross-validation for stability  
- (Optional) Plot decision boundaries for 2D datasets

---

## Key Learnings

- The importance of scaling in SVM to improve performance  
- How different kernels (Linear vs RBF) affect decision boundaries  
- Hyperparameter tuning with `C` and `gamma` for better accuracy  
- Using cross-validation to measure model robustness  
- Preprocessing steps to handle categorical data and missing values

---

## Tools Used

- Python (Pandas, NumPy)  
- Scikit-learn (SVC, LabelEncoder, StandardScaler, GridSearchCV, metrics)  
- Matplotlib for plotting

---

## Files in This Repo

- `Task_7_Hruthvik_H_N.ipynb` → Google Colab notebook with complete code
- `README.md` → Project documentation / this file

---

Feel free to connect in case of any doubts or to correct me
