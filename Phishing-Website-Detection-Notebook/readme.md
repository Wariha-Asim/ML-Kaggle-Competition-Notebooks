# Phishing Website Detection - Machine Learning Project

## Overview
This Jupyter notebook presents a comprehensive machine learning pipeline for detecting phishing websites using various classification algorithms. The project implements a complete workflow from data preprocessing to model evaluation and comparison.

## Key Features

### 🔍 Data Analysis & Preprocessing
- Loads and explores a phishing website dataset with 31 features and 11,055 entries
- Handles missing values and performs statistical analysis
- Implements feature scaling using StandardScaler

### 🤖 Machine Learning Models
1. **Support Vector Machine (SVM)**
   - Baseline implementation
   - Hyperparameter tuning using RandomizedSearchCV and GridSearchCV
   - Achieved 91.7-93.7% accuracy

2. **Random Forest Classifier**
   - Baseline implementation with 200 estimators
   - Achieved 95.7% accuracy with excellent ROC AUC score (0.991)
   - Best performing model among all

3. **XGBoost Classifier**
   - Hyperparameter tuning via RandomizedSearchCV
   - Comparative analysis with other models

### 📊 Model Evaluation & Comparison
- Accuracy, Precision, Recall, F1-Score
- Confusion matrix visualization for all models
- ROC curve analysis and AUC scores

### 📈 Visualization
- Confusion matrix heatmaps for all three models
- Feature importance analysis
- Model performance comparison charts

## Technical Highlights
- **Data**: 32 features including URL characteristics, domain information, and web traffic metrics
- **Preprocessing**: Standard scaling, train-test split (80-20)
- **Validation**: 5-fold cross-validation

## Project Structure
Phishing-Website-Detection-Notebook/
│
├── Phishing-Website-Detection-Notebook.ipynb   # Jupyter Notebook
├── README.md                                   # Project overview & results
├── dataset.csv                               
└── rf_submission.csv                            # Random Forest predictions CSV

## Results
The Random Forest model demonstrated superior performance with:
- ✅ 95.7% Accuracy
- 📊 0.991 ROC AUC Score
- ⚡ Excellent precision and recall metrics

> Among the three tested models, the **Random Forest Classifier** performed the best.  
> Therefore, a **CSV of its predictions** has been generated for reference and further analysis.

## Kaggle Notebook
You can view the full notebook on Kaggle: [https://www.kaggle.com/code/waarihaasim/phishing-detection-website-notebook)


