# __*Sales Prediction*__ (Time Series Regression Analysis)

## Overview
This is a time series regression analysis problem to predict store sales on data from Corporation Favorita. The goal is to develop a predictive model that forcasts unit sales for various items across different Favorita stores. Leveraging regression techniques, the analysis aims to uncover relationships between sales and key factors such as promotions, oil prices, holidays, and other external variables.

## Objectives
### Analytical
- Handle missing values in the datasets by imputation techniques such as mean, median, or mode.
- Address outliers in sales data that may skew the model's predictions by applying robust statistical methods or trimming techniques.
- Normalize or scale numerical features to ensure uniformity and improve model performance.
- Encode categorical variables using techniques such as one-hot encoding or label encoding.
- Build time series regression models such as SARIMA, ARIMA, XGBoost, Linear Regression etc. to capture seasonality and trends in sales data.
- Validate models using cross-validation techniques and assess their performance metrics such as RMSE (Root Mean Squared Error) or MAE (Mean Absolute Error).
- Create insightful visualizations and dashboards for sales analysis and forecasting.

### Business
- Enhance the accuracy of sales predictions.
- Provide valuable insights for optimizing business strategies.

## Methodology
Data Analysis

-  Descriptive Statistics: Calculate the  highest and lowest sales for each year, identifying significant sales trends.
- Impact of Wage Payments: Analyze the sales data on wage payment days, finding a slight increase in sales.

Hypothesis Testing

- Effect of Holidays on Sales: Conduct a Mann-Whitney U test to determine the impact of holidays on sales, leading to the rejection of the null hypothesis, indicating a significant effect.

Time Series Analysis

- Data Preparation: Apply differencing to remove trends and seasonality, confirm data stationarity using the Augmented Dickey-Fuller test.
- Modeling: Compare SARIMA, ARIMA, and Prophet models, with SARIMA showing the best performance based on error metrics.

Machine Learning Models

- Feature Engineering: Create date-related features and preprocess the data using pipelines for numerical and categorical features.
- Model Training: Train Linear Regression and XGBRegressor models, with XGBRegressor performing better.

Forecast Visualization

- Comparison Plots: Visualize observed sales vs. forecasts from different models to compare accuracy.

Conclusion and Recommendations

- Conclusion: SARIMA was the best performing statistical model, while XGBRegressor was the best machine learning model.

- Recommendations:
    - Enhance feature engineering with additional relevant features.
    - Use ensemble methods to combine forecasts.
    - Regularly update models with new data for improved accuracy.

## Article
Read the [Medium Article](https://medium.com/@gloriagivondo/predicting-sales-with-time-series-regression-a-project-at-corporation-favorita-ea74a601e665)

## Prerequisites
To use this application, you will need:
- Git
- Python
- Jupyter

## 💻 Setup
### Cloning the Repo
* In your terminal run:

        $ git clone https://github.com/GeGe-K/Time-Series-Regression-Analysis.git
        $ cd Time-Series-Regression-Analysis
        
### Create a virtual environment and activate
* Activate virtual environment

        $ python -m venv venv || python3 -m venv venv
        $ source venv/bin/activate || source venv\Scripts\activate

* Install the latest version of pip

        $ python -m pip install --upgrade pip to update Pip

* Install application dependancies and other modules

        $ pip install -r requirements.txt

### Running the code
* Click on `Run All` in the Jupyter Notebook

## 🐛 Known Bugs
There are no known bugs. Contact gloriagivondo@gmail.com in-case of any bugs.

## 📜 Author 
👩‍💻 __*Gloria Givondo*__
- [GitHub](https://github.com/GeGe-K)
- [LinkedIn](https://www.linkedin.com/in/gloria-givondo/)

## License
The content of this site is license under the MIT license
Copyright (c) 2023 **Gloria**
