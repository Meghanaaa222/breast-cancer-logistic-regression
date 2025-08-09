# breast-cancer-logistic-regression
# Breast Cancer Detection using Logistic Regression

# Project Overview
This project applies **Logistic Regression** to classify breast cancer tumors as **malignant** or **benign** using the [Breast Cancer Wisconsin Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html).  
The goal is to demonstrate end-to-end binary classification — from data preprocessing to model evaluation — including ROC and Precision-Recall analysis.



## Dataset Information
- **Source:** scikit-learn's built-in dataset
- **Shape:** 569 samples × 30 features
- **Class Distribution:**
  - Malignant (0): 212
  - Benign (1): 357

---

##  Methodology
1. **Data Loading & Exploration**
2. **Train-Test Split** (80% train / 20% test, stratified)
3. **Feature Scaling** with `StandardScaler`
4. **Logistic Regression** model training
5. **Evaluation** using:
   - Classification Report
   - Confusion Matrix
   - ROC Curve & AUC
   - Precision-Recall Curve
6. **Threshold Tuning** to improve recall

---

##  Results (Default Threshold = 0.5)
**Classification Report**
| Class       | Precision | Recall | F1-score |
|-------------|-----------|--------|----------|
| Malignant   | 0.98      | 0.98   | 0.98     |
| Benign      | 0.99      | 0.99   | 0.99     |

**Confusion Matrix**
[[41 1]
[ 1 71]]

**ROC AUC:** ~0.99
