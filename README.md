# Customer Churn Prediction

A machine learning project where I explored customer churn and built an XGBoost model to predict whether a customer is likely to leave.

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

I looked at things like:

- Churn distribution
- Customer tenure
- Monthly and total charges
- Contract type
- Internet service
- Payment method
- Support services
- Correlations and feature relationships

Some noticeable patterns were that month-to-month customers and customers with shorter tenure tended to churn more.

## Model

The main model used was **XGBoost**.

I also compared the results of using PCA with the original features to see how dimensionality reduction affected the model.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn

## Dataset

Telco Customer Churn dataset with 7,043 customer records.

The target variable is `Churn`, which indicates whether a customer left the service.
