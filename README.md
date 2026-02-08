# Weather forecast in Seoul, South Korea

## Introduction

In this project, I use machine learning techniques in Python to predict the average temperature for the next day in Seoul, South Korea.

The dataset is composed of several forecast variables for the next day, maximum and minimum temperatures of the current day, 
and auxiliary geographic variables were collected over five years by the Korean Meteorological Service in Seoul, South Korea. 
The output variable is the next day's average temperature (NextDayAvTemp).

The main result of this project is the use of different techniques in the data preparation and modelling stages. A potential stakeholder could be the Korean Meteorological Service, which could use these predictive models to enhance the accuracy of weather forecasts.

## Technical Details

- **Dataset**: The dataset weather_data.csv contains around 7,000 rows and 23 columns.  
- **Data Exploration**: Performed basic data exploration, such as checking data types, null values, and duplicates.
- **Feature Engineering**: Includes one-hot encoding for categorical variables and Min-Max Scaling for numerical data.
- **Imputation**: Missing values are imputed using K-Nearest Neighbors (KNN).
- **Feature Selection**: Selected features using statistical methods to enhance model performance.
- **Models**: Various regression models from Scikit-learn and xgboost packages are implemented, including:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - ElasticNet Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - AdaBoost Regressor
  - Support Vector Regressor
  - K-Nearest Neighbors Regressor
  - Neural Network Regressor
  - Gaussian Process Regressor
  - XGBoost Regressor
- **Evaluation**: Models are ranked using metrics such as r-square score, Mean Absolute Error (MAE), and Mean Squared Error (MSE). 
Additionally, learning curves are plotted to check for potential overfitting.

## Impact

Achieved 93% coefficient of determination performance, delivering highly accurate weather forecasts that support better planning and decision-making for local authorities and businesses in Seoul.

## Visuals

Table, histogram, and scatter plot.

## Dependency Versions

The Python environment used in this project can be set up in Anaconda using the python_env.yaml file.
