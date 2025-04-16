# 💼 Salary Prediction using Machine Learning

This project predicts employee salaries based on features such as education level, gender, age, years of experience, and job title. It demonstrates a complete end-to-end machine learning pipeline using Python and scikit-learn.

---

## 📁 Dataset Description

The dataset contains the following columns:
- `Gender`
- `Education Level`
- `Job Title`
- `Years of Experience`
- `Age`
- `Salary` (Target)

---

## 🔧 Workflow Summary

### 1. Data Cleaning
- Checked for missing values
- Dropped rows with <1% missing data
- Standardized inconsistent categorical values (e.g., “PhD” vs “phD”)

### 2. Exploratory Data Analysis (EDA)
- Statistical summaries
- Distribution plots for numerical & categorical variables
- Identified outliers and data imbalance

### 3. Feature Engineering & Preprocessing
- `OneHotEncoder` for categorical columns
- `StandardScaler` for numeric features (when required)
- Combined using `ColumnTransformer` and `Pipeline`

### 4. Model Training & Evaluation
Tested multiple models:
- Linear Regression
- Random Forest Regressor
- Decision Tree Regressor
- ElasticNet
- KNN
- SVR
- XGBoost

Metrics used:
- MAE
- MSE
- RMSE
- R² Score

Cross-validation applied for robustness.

### 5. Hyperparameter Tuning
- Used `GridSearchCV`

### 6. Export
- Best model saved using `joblib`
- Model simulation prediction




