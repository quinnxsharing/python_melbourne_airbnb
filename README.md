# Airbnb Listing Price Prediction in Melbourne

This GitHub repository hosts a Jupyter Notebook containing a comprehensive analysis and predictive model for forecasting Airbnb listing prices in Melbourne. The notebook is structured into multiple parts, each focusing on different aspects of the analysis and prediction process.

## Problem Description and Initial Data Analysis

The initial section of the notebook involves data exploration and analysis. It includes loading the dataset, identifying variable types, exploring basic statistics, visualizing price distributions, and detecting missing values.

### Forecasting Problem

The primary objective is to forecast the listing price of Airbnb properties in Melbourne accurately. Accurate price forecasting is essential for making informed business decisions affecting hosts, customers, and Airbnb as a company. Evaluation of the forecasting model is based on the Mean Squared Error (MSE) method, which measures the squared average of the difference between predicted and actual prices.

### Types of Variables

The dataset comprises 7,000 observations with 71 variables, including 34 numerical and 27 categorical variables. Numerical variables cover various features such as accommodation details and host-related metrics, while categorical variables include textual information like property descriptions and neighborhood details.

### Data Summary and Main Data Characteristics

A summary of the dataset is provided, showcasing key statistics like count, mean, standard deviation, min, max, and quartile values for each variable. This summary aids in understanding the distribution and range of values within the dataset.

### Missing Values

A thorough examination reveals missing or null values in 23 out of 71 variables, totaling 11,828 missing values. Addressing these missing values is vital for ensuring the accuracy and reliability of subsequent analysis and predictions.

## Data Cleaning, Missing Observations, and Feature Engineering

This section primarily focuses on data preprocessing tasks, including reading and combining datasets, transforming data types, creating binary features, and imputing missing values. Preprocessing categorical columns involves categorizing top frequent values and grouping others as 'other' to manage feature dimensions.

## Exploratory Data Analysis (EDA)

The exploratory data analysis (EDA) reveals insights into the relationship between features and listing prices. Scatter plots and correlation analysis for numerical features and box plots for categorical features provide valuable insights into price variation.

## Prediction Model Development

The GitHub repository contains code for predicting Airbnb rental prices using machine learning models. Two key models implemented are Decision Tree Regression and XGBoost Regressor. Each model undergoes default implementation, tuning hyperparameters using grid search, and optimization to improve performance.

### Decision Tree Regression

This model is implemented with default parameters initially and then tuned using grid search to enhance performance. The optimized decision tree model yields improved predictions for listing prices.

### XGBoost Regressor

Similarly, the XGBoost regressor undergoes default training followed by hyperparameter tuning using grid search. Multiple versions of the XGBoost model with different parameter settings are implemented to compare performance and optimize predictions.

## Model Deployment

Once the models are trained and optimized, predictions for rental prices are generated on a test dataset. Predictions are exported to CSV files for submission and further analysis.

