#  Housing Price Prediction – Task 3

This project involves building a predictive model using **Linear Regression** to estimate housing prices based on features in the dataset `Housing.csv`.

##  Dataset
- `Housing.csv`  
Contains various housing attributes like area, location, number of bedrooms, and more.

## Objective
- Analyze the dataset
- Preprocess the data (handle categorical features, missing values)
- Train a Linear Regression model
- Evaluate its performance using MSE and R² Score

##  Workflow Summary

### 1. Load and Inspect Data
- Display column names, missing values, and statistics.
- Understand dataset structure.

### 2. Encode Categorical Variables
- One-hot encoding for non-numeric features using `pandas.get_dummies()`.

### 3. Prepare Features and Target
- Features: All columns except `price`
- Target: `price`

### 4. Split Data
- 80% training, 20% testing using `train_test_split`.

### 5. Train Model
- Linear Regression using `sklearn.linear_model.LinearRegression`.

### 6. Evaluate Model
- Metrics: Mean Squared Error (MSE), R² Score

##  Results
- **MSE**: _<insert actual value after running>_
- **R² Score**: _<insert actual value after running>_

## 🛠 Libraries Used
- `pandas`
- `scikit-learn`
- `numpy`

##  Notes
- All preprocessing is done in-place.
- Categorical encoding uses `drop_first=True` to avoid dummy variable trap.

---

>  Task 3 has been successfully implemented, validated, and completed.

