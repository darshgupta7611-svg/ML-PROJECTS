# Insurance Claims — EDA & XGBoost

A machine learning project focused on exploring insurance claim data and predicting claim amounts using XGBoost.

## About

This project explores an insurance dataset to understand the factors and patterns associated with claim amounts. It combines extensive exploratory data analysis with an XGBoost regression model for claim prediction.

## Files

- `Insurance_Claims.ipynb` — Main notebook containing EDA, visualizations, modeling, and analysis

## Dataset

Insurance claims dataset containing customer demographics, health-related attributes, and claim amounts.

## Tools Used

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

## Key Steps

1. Data cleaning and preprocessing
2. Univariate and bivariate EDA
3. Distribution analysis using histograms and KDE
4. Categorical analysis using cross-tabulation
5. Correlation and feature analysis
6. Outlier analysis
7. Feature encoding
8. XGBoost regression
9. Hyperparameter tuning using GridSearchCV
10. Residual analysis and model evaluation

## Key Insights

- Claim amounts are strongly right-skewed.
- Most claims are concentrated at lower values, with fewer high-value claims.
- Several customer characteristics show noticeable relationships with claim amounts.
- XGBoost captured most of the underlying patterns but showed larger errors for some high-value claims.
