# 📊 Heart Disease Prediction - End-to-End Machine Learning Workflow

This project implements a complete **end-to-end machine learning pipeline** for predicting **Heart Disease** using the `heart.csv` dataset.  
It covers **data preprocessing, model training (baseline & tuned), evaluation, comparison, ranking, and visualization**, all the way to generating predictions for deployment.


## 🚀 Workflow Overview

1. **Data Preprocessing**
   - Loaded and explored dataset (`heart.csv`).
   - Encoded categorical features: `Sex`, `ChestPainType`, `RestingECG`, `ExerciseAngina`, `ST_Slope`.
   - Scaled numerical features using `StandardScaler`.
   - Performed **train-test split** (80-20) with stratification.

2. **Baseline Models**
   - **Logistic Regression**: baseline performance check.
   - **Random Forest**: trained with default parameters.
   - **XGBoost**: implemented with default params.
   - **CatBoost**: baseline with default params.

3. **Hyperparameter Tuning**
   - **Random Forest**: tuned using `RandomizedSearchCV`.
   - **XGBoost**: tuned with search over `n_estimators`, `max_depth`, `learning_rate`, etc.
   - **CatBoost**: tuned with `iterations`, `depth`, `learning_rate`, `l2_leaf_reg`, and `border_count`.

4. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - ROC-AUC
   - Classification Reports
   - Confusion Matrices

5. **Model Comparison & Ranking**
   - Compiled results for all models (baseline & tuned).
   - Ranked models using Accuracy, F1 Score, and ROC-AUC.
   - ✅ **Selected XGBoost (Tuned) as the best-performing model.**

6. **Visualizations (XGBoost Tuned)**
   - Confusion Matrix Heatmap
   - ROC Curve with AUC Score
   - Precision-Recall Curve
   - Feature Importance Plot

7. **Final Output**
   - Created `submission.csv` with predictions from **XGBoost Tuned**.

## 🛠️ Tech Stack
- **Python**
- **Scikit-learn**
- **XGBoost**
- **CatBoost**
- **Matplotlib / Seaborn**
- **Pandas & NumPy**


## ✅ Key Takeaways
- Built multiple ML models (Logistic Regression, Random Forest, XGBoost, CatBoost).
- Applied **hyperparameter tuning** for performance improvement.
- Compared models across multiple evaluation metrics.
- Interpreted results with **visualizations**.
- Selected **XGBoost Tuned** as the final best model.
- Exported predictions into a structured CSV file for further use.


## 📂 Project Structure
Heart Failure Prediction
├── Heart Failure Prediction-XgBoost & CatBoost.ipynb # End-to-end ML workflow
├── xgb(tuned)_submission.csv # Final predictions from best model
├── README.md # Project documentation


## 🌟 Results
- **Best Model:** XGBoost (Tuned)
- **Use Case:** Helps in predicting heart disease risk for healthcare applications.

## Kaggle Notebook
You can view the full notebook on Kaggle: [https://www.kaggle.com/code/waarihaasim/heart-failure-prediction-xgboost-catboost]


