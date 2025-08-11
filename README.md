# 🩺 Advanced Diabetes Prediction Model

This project predicts whether a person is diabetic based on medical attributes like glucose level, BMI, age, and blood pressure. It uses advanced ML techniques for high accuracy and explainability.

## 📌 Features
- **Models Used**: Logistic Regression, Random Forest, XGBoost
- **Techniques**:
  - Data preprocessing (handling missing values, scaling)
  - SMOTE for handling class imbalance
  - Hyperparameter tuning (RandomizedSearchCV)
  - SHAP explainability for feature importance
- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-score, ROC-AUC
  - Confusion Matrix and ROC Curve visualization

## 📊 Dataset
- **Source**: [PIMA Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Shape**: 768 rows × 9 columns
- **Target**: `Outcome` (0 = Non-diabetic, 1 = Diabetic)

## 🚀 Results
- Best model: **Random Forest**
- ROC-AUC: **~0.93**
- SHAP analysis revealed Glucose, BMI, and Age as key predictors

## 📸 Visualizations
- Feature importance (SHAP)
- Confusion matrix
- ROC curve

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- SHAP
- Matplotlib, Seaborn

---
⭐ **If you found this useful, give it a star on GitHub!**
