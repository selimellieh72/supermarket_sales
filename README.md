# Supermarket Store Sales Analysis

![Hero Image](images/hero.png)

## Project Overview

This project focuses on the comprehensive analysis of supermarket store sales data. The primary goal is to uncover insights through exploratory data analysis, employ various machine learning techniques to predict sales, and understand the effectiveness of different models. This analysis is particularly useful for identifying key drivers of sales and optimizing business strategies in retail.

## Data Source

The dataset used in this project is sourced from Kaggle, a platform that hosts various datasets for analytical competitions and exploratory data analysis.

## Key Features of the Project

- **Exploratory Data Analysis (EDA)**: Conducted thorough EDA to understand correlations between features, identify gaps and outliers in the data, and visualize the density and distribution of the data using Kernel Density Estimation (KDE).
- **Outlier Removal**: Implemented techniques to identify and remove outliers from the dataset to improve the accuracy and reliability of the predictive models.
- **Clustering with KMeans**: Utilized KMeans clustering to identify distinct groups within the data, aiding in more targeted analysis and understanding of customer segments.
- **KFold Cross-Validation**: Employed KFold cross-validation to ensure robustness and reliability in model evaluation, avoiding overfitting and ensuring the generalizability of the models.
- **Predictive Modeling**: Developed and compared multiple regression models, including:
  - RandomForestRegressor
  - LinearRegression
  - ElasticNet
  - KNeighborsRegressor
  - XGBRegressor

## Model Performance

The models were evaluated based on various metrics, including RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), MSLE (Mean Squared Log Error), and MAPE (Mean Absolute Percentage Error). Here are the summarized results:

- **RandomForestRegressor**

  - Average RMSE: 342,577,049.01
  - Average MAE: 15,037.39
  - Average MSLE: 0.1084
  - Average MAPE: 28.73%

- **LinearRegression**

  - Average RMSE: 286,936,149.93
  - Average MAE: 13,988.30
  - Average MSLE: 0.0938
  - Average MAPE: 27.10%

- **ElasticNet**

  - Average RMSE: 286,382,409.17
  - Average MAE: 13,999.42
  - Average MSLE: 0.0938
  - Average MAPE: 27.17%

- **KNeighborsRegressor**

  - Average RMSE: 348,162,009.06
  - Average MAE: 15,365.76
  - Average MSLE: 0.1111
  - Average MAPE: 29.54%

- **XGBRegressor**
  - Average RMSE: 383,582,019.93
  - Average MAE: 15,843.04
  - Average MSLE: 0.1207
  - Average MAPE: 30.03%

## Conclusion

The analysis revealed no high correlation between the data, suggesting that the features provided diverse and independent information useful for predicting sales. The results showcase the effectiveness of each model and provide insights into their applicability for sales prediction in retail scenarios.
