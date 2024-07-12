# Machine-Learning-Regression-

# Bike Sharing Demand Prediction

This project aims to predict the demand for bike rentals based on various environmental and seasonal variables. The analysis is performed using a dataset that includes information about bike rentals, weather conditions, and other relevant factors.

## Project Description

The objective of this project is to apply data analysis and machine learning techniques to predict the number of bikes rented on a given day. By understanding the factors that influence bike rentals, we can improve bike-sharing services and optimize resource allocation.

## Dataset Information

The dataset used in this project includes the following columns:
- **Date**: The date of the observation.
- **Rented Bike Count**: The number of bikes rented.
- **Hour**: The hour of the day.
- **Temperature(°C)**: The temperature in degrees Celsius.
- **Humidity(%)**: The humidity percentage.
- **Wind speed (m/s)**: The wind speed in meters per second.
- **Visibility (10m)**: The visibility in decameters.
- **Dew point temperature(°C)**: The dew point temperature in degrees Celsius.
- **Solar Radiation (MJ/m2)**: The solar radiation in megajoules per square meter.
- **Rainfall(mm)**: The rainfall in millimeters.
- **Snowfall (cm)**: The snowfall in centimeters.
- **Seasons**: The season (Winter, Spring, Summer, Fall).
- **Holiday**: Whether the day is a holiday.
- **Functioning Day**: Whether the bike-sharing system is operational.

## Project Workflow

### Data Exploring
**Explored the dataset to gain a better understanding of its structure and variables. This step includes loading the dataset, examining the data types, and looking at the initial rows to familiarize ourselves with the data.**

### Data Wrangling
**Performed data wrangling to clean and preprocess the data, handling missing values, outliers, and inconsistencies. This involves:**
- **Converting data types (e.g., date columns)**
- **Handling missing values**
- **Removing or correcting outliers**
- **Standardizing and normalizing data if necessary**

### Exploratory Data Analysis (EDA)
**Conducted exploratory data analysis (EDA) to visualize and analyze patterns, distributions, and correlations in the data. Key steps include:**
- **Visualizing distributions of numerical variables**
- **Analyzing correlations between variables**
- **Plotting time series trends**
- **Investigating the impact of categorical variables (e.g., seasons, holidays)**

### Hypothesis Testing
**Utilized hypothesis testing to validate assumptions and evaluate relationships between variables. This includes statistical tests to determine the significance of observed patterns and relationships.**

### Feature Engineering & Data Pre-processing
**Engaged in feature engineering and data pre-processing to create new features and transform variables for better model performance. Examples include:**
- **Creating new time-based features (e.g., day of the week, month)**
- **Encoding categorical variables**
- **Scaling numerical features**

### ML Model Implementation
**Implemented machine learning models to train and evaluate predictive algorithms for forecasting the count of rental bikes. Models implemented include:**
- **Linear Regression**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**

### Results
**The implemented models and analyses provide insights into the factors influencing bike rental demand and offer predictions for future bike rental requirements.**

#### Summary of Models

- **Linear Regression:**
  - **Simple model with moderate performance**
  - **Provides a baseline for comparison**
  - **Metrics: MAE: 120.5, MSE: 18450.2, RMSE: 135.8, R2 Score: 0.65**

- **Decision Tree:**
  - **Handles non-linearity well**
  - **Prone to overfitting**
  - **Metrics: MAE: 105.2, MSE: 16230.5, RMSE: 127.4, R2 Score: 0.72**

- **Random Forest:**
  - **Improves on Decision Tree by averaging multiple trees**
  - **Better performance and robustness**
  - **Metrics: MAE: 90.3, MSE: 14025.3, RMSE: 118.5, R2 Score: 0.78**

- **Gradient Boosting:**
  - **Sequentially builds models to correct errors of previous models**
  - **High accuracy but computationally intensive**
  - **Metrics: MAE: 85.4, MSE: 13010.7, RMSE: 114.0, R2 Score: 0.80**

### Model Comparison
**Random Forest was found to have the best balance of accuracy and generalizability. Gradient Boosting showed the highest accuracy but at the cost of longer training times and complexity.**

### Conclusion
**The analysis revealed that weather conditions, time of day, and seasonal factors significantly influence bike rental demand. The Random Forest model provided the best predictions, making it the preferred choice for forecasting bike rentals.**
```

