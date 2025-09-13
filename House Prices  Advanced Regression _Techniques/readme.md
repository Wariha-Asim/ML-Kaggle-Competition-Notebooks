# 🏠 House Prices - Advanced Regression Techniques

## 📊 Project Overview
This project predicts residential home prices in Ames, Iowa using advanced machine learning techniques. The solution implements a comprehensive end-to-end pipeline with extensive feature engineering, multiple model experimentation, and hyperparameter optimization to capture complex relationships between house features and sale prices.

## 🛠️ Tech Stack
- **Python** • **Pandas** • **NumPy**
- **Scikit-learn** • **XGBoost** • **Matplotlib** • **Seaborn**
- **Jupyter Notebook**

## 📈 Key Features

### Data Preprocessing
- Handled missing values for both numerical (median imputation) and categorical (mode imputation) features
- Encoded categorical variables using Label Encoding
- Performed comprehensive data exploration and cleaning

### Feature Engineering
- 79 original features covering property details
- Key numerical features: LotArea, GrLivArea, TotalBsmtSF, GarageArea, FullBath
- Key categorical features: Neighborhood, MSZoning, RoofStyle, CentralAir

### Models Implemented
- **Decision Tree Regressor** (Baseline & Tuned)
- **Random Forest Regressor** (Baseline & Tuned)
- **XGBoost Regressor** (Baseline & Tuned)

### Model Evaluation
- Cross-validation with 80/20 split
- Multiple regression metrics: MAE, RMSE, R²
- Comprehensive model comparison and ranking
- XGBoost demonstrated superior performance

## 📁 Project Structure
House-Prices-Regression/
├── House Prices - Advanced Regression Techniques.ipynb # Main notebook
├── submission.csv # Competition predictions
├── requirements.txt # Dependencies
└── README.md # Project documentation

## 🎯 Results
- **Best Model**: XGBoost (Baseline)
- **Validation MAE**: $16,788
- **Validation RMSE**: $26,125
- **Validation R²**: 0.911
- **Key Insight**: XGBoost baseline outperformed tuned models, proving strong default configurations can be highly effective

## 📊 Data Insights
- XGBoost demonstrated superior predictive performance for housing price regression
- Feature importance analysis revealed key price determinants
- Complex non-linear relationships were effectively captured by ensemble methods
- Proper data preprocessing proved critical for model accuracy

## 🔗 Links
- **Kaggle Notebook**: [House Prices Advanced Regression Notebook](https://www.kaggle.com/code/waarihaasim/house-prices-advanced-regression-notebook)
- **Kaggle Competition**: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- **GitHub Repository**: [ML Kaggle Competition Notebooks](https://github.com/Wariha-Asim/ML-Kaggle-Competition-Notebooks/blob/main/House%20Prices%20%20Advanced%20Regression%20_Techniques/house-prices-advanced-regression-techniques.ipynb)

## 👩‍💻 Author
**Waariha Asim**

- Kaggle: [@waarihaasim](https://www.kaggle.com/waarihaasim)
- GitHub: [@Wariha-Asim](https://github.com/Wariha-Asim)

## 📄 License
This project is open source and available under the MIT License.
*This project was developed as part of Kaggle's House Prices competition, demonstrating advanced regression techniques for predictive modeling on structured housing data.*
