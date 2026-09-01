# Data Science HW #02 

Regression & Classification Modeling 

## Contents

| File | Description |
|---|---|
| `Datascience_HW#02 - 401101727.ipynb` | Main notebook |
| `pic1.png` – `pic4.png` | Figures referenced/exported in the notebook |

## Assignment Overview

### 1. Regression Methods
- Linear, Kernel, Ridge, and LASSO Regression
- Explanation of the **kernel trick** and how it improves regression by operating in a high-dimensional feature space without explicitly computing coordinates in it
- Evaluation via MSE, MAE, MAPE, R²
- Discussion: choice of best metric, when each model is preferable, and how the kernel trick helps

### 2. Binary Classification Methods
- Logistic Regression, SVM, Kernel SVM, KNN (tuned K), Decision Trees (tuned max-depth), Random Forests
- Evaluation via Accuracy, Precision, Recall, F1, Confusion Matrix, ROC/AUC
- Discussion: best metric justification, decision tree regularization techniques, Linear vs. Kernel SVM

### 3. Multiclass Classification Methods
- At least 4 classes; models spanning Multiclass SVM, Multiclass Logistic Regression (OVR & multinomial), Multiclass KNN, Decision Trees, and boosting methods (XGBoost, LightGBM, AdaBoost, CatBoost)
- Evaluation via per-class Precision/Recall, F1 (Macro/Micro/Weighted)
- Discussion: best multiclass metric, extending KNN/Decision Trees to multi-label problems, evaluation strategy for a multi-label football-player classification example

