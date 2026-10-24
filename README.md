# 🤖 Machine Learning Projects Portfolio

A curated collection of end-to-end Machine Learning workflows implemented in Python and Google Colab, covering exploratory data analysis (EDA), advanced feature preprocessing, and predictive modeling for classification and regression tasks.

---

## 📂 Repository Overview

### 1. Telecom Customer Churn Prediction
* **Notebook:** `churn.ipynb`
* **Domain:** Telecommunications / Customer Retention
* **Objective:** Predict whether telecom subscribers will cancel their services (churn) based on customer profiles, account tenure, contract types, and service usage.
* **Key Highlights:**
  - **Exploratory Data Analysis (EDA):** Identified behavioral drivers behind churn, assessing call frequency, service subscriptions, and billing patterns.
  - **Data Preprocessing:** Handled categorical encoding, missing values, and imbalanced target distributions.
  - **Modeling & Evaluation:** Applied classification algorithms to detect high-risk churn customers, focusing on precision, recall, and ROC-AUC metrics to minimize false negatives in customer retention.

---

### 2. House Prices — Advanced Regression Techniques
* **Notebook:** `House_Prices_ML_Learning_v2.ipynb`
* **Dataset:** Kaggle *House Prices - Advanced Regression Techniques*[cite: 3]
* **Objective:** Predict residential property final prices (`SalePrice`) using 79 explanatory features[cite: 3].
* **Key Highlights:**
  - **Exploratory Data Analysis (EDA):** Evaluated `SalePrice` distribution skewness and extracted strong correlations with features such as `OverallQual` ($r \approx 0.79$) and `GrLivArea` ($r \approx 0.71$)[cite: 3].
  - **Context-Aware Imputation:** Applied domain-specific missing value handling (e.g., mapping explicit lack of garages, pools, and basements to `"None"`, and imputing `LotFrontage` using neighborhood medians)[cite: 3].
  - **Feature Engineering:** Structured pipeline preprocessing including ordinal encoding for rated conditions and baseline preparation[cite: 3].

---

## 🛠️ Stack & Libraries

* **Language:** Python 3[cite: 4]
* **Data Processing:** Pandas, NumPy[cite: 3, 4]
* **Visualization:** Matplotlib, Seaborn[cite: 3, 4]
* **Machine Learning:** Scikit-Learn[cite: 3, 4]
* **Platform:** Google Colab[cite: 3, 4]

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone [https://github.com/ahmedsaayda/Machine-learning.git](https://github.com/ahmedsaayda/Machine-learning.git)
   cd Machine-learning
