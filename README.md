# A Yen for the Future

![Yen Photo](readme-photo.png)

## Background

The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.

In this assignment, I test various time-series tools to predict future movements in the value of the Japanese yen versus the U.S. dollar.

The Jupyter Notebooks detail:

1. Time Series Forecasting
2. Linear Regression Modeling


- - -

#### Time-Series Forecasting

In this notebook, I loaded historical Dollar-Yen exchange rate futures data and applied time series analysis and modeling to determine whether there is any predictable behavior.

The Time-Series Jupyter Notebook outlines the following:

1. Decomposition using a Hodrick-Prescott Filter (Decomposing the Settle price into trend and noise).
2. Forecasting Returns using an ARMA Model.
3. Forecasting the Settle Price using an ARIMA Model.
4. Forecasting Volatility with GARCH.

#### Linear Regression Forecasting

In this notebook, I builT a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with *lagged* Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

The Regression Analysis Jupyter Notebook contains the following:

1. Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
2. Fitting a Linear Regression Model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.
