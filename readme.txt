## 📌 Project Overview

This project focuses on **credit risk analysis** using several machine learning models and **eXplainable AI (XAI)** techniques. Multiple classifiers and explanation tools were used to assess both **model performance** and **interpretability**. Each team member contributed different models and XAI tools, and evaluations were done using various performance metrics.

---

## 👥 Team Contributions

### 🔹 Youssef

* **Logistic Regression**

  * Accuracy: `0.5371`
  * Techniques: Coefficient Importance Plot, Odds Ratios, Confusion Matrix

* **Naive Bayes**

  * Accuracy: `0.5425`

* **Support Vector Machine (SVM)**

  * Techniques: LIME, SHAP, Odds Ratio, Confusion Matrix

---

### 🔹 Yasmin

* **Decision Tree**

  * Accuracy: `0.6534`
  * Precision: `0.6487`
  * Recall: `0.6534`
  * F1 Score: `0.6503`
  * Techniques: Decision Path, Feature Importance, SHAP, LIME, Global Surrogate Model

* **AdaBoost**

  * Validation Accuracy: `0.6209`
  * Test Accuracy: `0.6258`
  * Techniques: Feature Importances, Permutation Importance, LIME, Surrogate Model, LOFO Importance

* **Random Forest**

  * Validation Accuracy: `0.7246`
  * Techniques: Feature Importance (Gini), Permutation Importance, PDP, ICE, Decision Paths, SHAP

* **Multi-Class Logistic Regression**

  * Validation Accuracy: `0.5246`
  * Techniques: PDP, GLM Model, SHAP

---

### 🔹 Mommen

* **Random Forest**

  * Accuracy: `0.80`
  * Techniques: Feature Importance, PDP, Permutation Importance, LIME

* **XGBoost**

  * Accuracy: `0.76`
  * Techniques: Feature Importance, PDP, Permutation Importance, LIME, SHAP

* **Bagging Classifier (with Decision Tree)**

  * Accuracy: `0.80`
  * Techniques: Feature Importance, PDP, Permutation Importance, LIME, SHAP

---

### 🔹 Raneem

Used Models: SVM, Neural Network (NN), Random Forest, XGBoost
Techniques Used: SHAP, LIME, PDP, Permutation Importance, ROC Curve, ALE (for SVM and NN)

#### Neural Network:

* Accuracy: `0.60`
* Confusion Matrix:

  ```
  [[ 61  10  58]
   [  7 143  89]
   [ 31  89 220]]
  ```

#### Random Forest:

* Accuracy: `0.81`
* Confusion Matrix:

  ```
  [[39  0 23]
   [ 0 83 21]
   [ 9 15 163]]
  ```

#### XGBoost:

* Accuracy: `0.76`
* Confusion Matrix:

  ```
  [[1188   26  522]
   [  72 2432  847]
   [ 411  691 4421]]
  ```

---

## 🧠 XAI Techniques Used

* SHAP (SHapley Additive exPlanations)
* LIME (Local Interpretable Model-Agnostic Explanations)
* PDP (Partial Dependence Plots)
* ICE (Individual Conditional Expectation)
* Permutation Importance
* Feature Importance (Gini-based, Coefficients, etc.)
* Odds Ratios (for Logistic Regression)
* Confusion Matrix
* ROC Curve
* ALE (Accumulated Local Effects)
* LOFO (Leave-One-Feature-Out) Importance
* Decision Paths
* Global Surrogate Models

---

Let me know if you'd like help turning this into a downloadable `README.md` file or uploading it to GitHub.
