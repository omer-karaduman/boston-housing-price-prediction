# 🏡 Boston Housing Price Prediction

This project uses a **Linear Regression Model** to predict Boston house prices. It also includes **data preprocessing** and **data visualization** steps.

## 📂 Content
- **Dataset:** Boston Housing Dataset  
- **Data Preprocessing:** Missing Value Analysis (MVA), Scaling  
- **Visualization:** Correlation Analysis, Distribution Graphs  
- **Model:** Linear Regression  
- **Model Evaluation:** Root Mean Squared Error (RMSE)  

## 📌 Technologies Used
- Python  
- Numpy, Pandas  
- Matplotlib, Seaborn  
- Plotly  
- Scikit-Learn  

## 📊 About the Dataset
The **Boston Housing Dataset** consists of **14 columns**. The target variable is the **Price column (MEDV)**, which depends on 13 other features.  
In the **Correlation Analysis**, we identified four key features that strongly correlate with the price:

- **LSTAT** (Negative Correlation)  
- **PTRATIO** (Negative Correlation)  
- **RM** (Positive Correlation)  
- **TAX** (Negative Correlation)  

## 📊 Dataset Features
- **CRIM:** Crime rate per capita for each town.  
- **ZN:** Percentage of residential areas larger than 25,000 sq.ft.  
- **INDUS:** Percentage of non-retail businesses in a town.  
- **CHAS:** Proximity to the Charles River (1 = close, 0 = not).  
- **NOX:** Nitrogen oxide (NOx) concentration, an indicator of air pollution.  
- **RM:** Average number of rooms in a house.  
- **AGE:** Percentage of properties built before 1940.  
- **DIS:** Weighted distances to five Boston business districts.  
- **RAD:** Index of access to circular highways.  
- **TAX:** Property tax rate per $10,000.  
- **PTRATIO:** Student-teacher ratio for each town.  
- **B:** A value calculated based on the percentage of black residents in the town.  
- **LSTAT:** Percentage of the population in the lower-income group.  
- **PRICE:** Median value of homes owned (in $1000).  

## 📂 Dataset  
You can download the dataset from Kaggle:  
🔗 [Boston Housing Dataset on Kaggle](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices) 
