# Walmart-Store-sales-Forecasting

## **Datasets**
Utilized the Walmart Recruiting - Store Sales Forecasting dataset obtained from Kaggle. The dataset includes the following CSV files:
- `train.csv`
- `stores.csv`
- `features.csv`

## **Machine Learning Models**
Implemented several regression models to predict store sales:
- **Linear Regression**
- **Random Forest Regression**
- **K Neighbors Regression**
- **XGBoost Regression**
- **Custom Deep Learning Neural Network**

## **Data Preprocessing**
Performed the following preprocessing steps:
- Addressed missing values by filling them with the median of their respective columns.
- Merged and manipulated datasets to create a comprehensive dataset.
- Split the date column into **Year**, **Month**, and **Week**.
- Aggregated weekly sales and detected outliers.
- Applied one-hot encoding to categorical variables and normalized numerical columns.
- Employed Recursive Feature Elimination to select important features.

## **Model Training and Evaluation**
- Split the dataset into **training** and **testing** sets.
- Trained each model and evaluated their performance using the following metrics:
  - **Accuracy**
  - **Mean Absolute Error**
  - **Mean Squared Error**
  - **Root Mean Squared Error**
  - **R2 Score**

## **Model Comparison**
Compared the performance of different regression models. The **Random Forest Regression** model achieved the highest accuracy of **97.89%**.
