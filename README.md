# Customer Churn Prediction

A machine learning project where I built an XGBoost model to predict whether a customer is likely to leave.

## What I did

- Cleaned and explored the dataset
- Performed detailed EDA
- Handled missing values
- Created a few useful features
- One-hot encoded categorical columns
- Used PCA for dimensionality reduction
- Used SMOTE to handle class imbalance
- Trained an XGBoost classifier
- Tuned the model using RandomizedSearchCV
- Compared models with and without PCA

## EDA

- Churn distribution
- Customer tenure
- Monthly and total charges
- Contract type
- Internet service
- Payment method
- Support services
- Correlations and feature relationships
## Model

The main model used was **XGBoost**.

I compared the results of using PCA with the original features 

## libraries used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn
