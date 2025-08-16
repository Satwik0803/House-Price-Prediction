# House Price Prediction

This project applies **Machine Learning** techniques to predict house prices using regression models.  
It demonstrates the full workflow including **data preprocessing, feature analysis, model training, evaluation, and prediction**.

---

## Tech Stack
- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  

---

## Requirements

Install the following dependencies before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

# Project Workflow

## 1. Data Preprocessing
- Loaded the dataset using pandas.
- Handled missing values and cleaned data.
- Scaled features using StandardScaler from scikit-learn.

## 2. Exploratory Data Analysis (EDA)
- Used matplotlib and seaborn for visualization.
- Explored feature distributions and correlations with the target variable SalePrice.

## 3. Feature Selection
- Selected important features with higher correlation to SalePrice.

## 4. Model Training
- Split dataset into training and testing sets using train_test_split.
- Trained a Linear Regression model from scikit-learn.

## 5. Evaluation
Evaluated the model using metrics:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## 6. Prediction
- Generated predictions on unseen test data.

## Results
- Built and evaluated a regression model for predicting house prices.
- Achieved insights into the most influential features affecting SalePrice.
- Visualized correlations and performance metrics to assess prediction accuracy.

## Model Performance (Errors)
- Mean absolute error: 19676.36117015432
- Mean squared error: 931750864.5052171
- Root mean squared error: 30524.594419995447
