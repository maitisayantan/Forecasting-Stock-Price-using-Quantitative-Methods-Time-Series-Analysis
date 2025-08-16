**Forecasting Stock Prices using Quantitative Methods: Time Series Analysis**

**Project Overview**

This project explores quantitative methods for stock price forecasting, combining classical time series models with deep learning approaches. The primary goal was to analyze patterns in stock market data, ensure stationarity, and build predictive models capable of accurately capturing both linear and nonlinear dynamics in stock price movements.

**Time Series Decomposition and Stationarity**

The analysis began with decomposing GOOGLE stock price data into its four fundamental components: level, trend, seasonality, and residuals. To confirm stationarity, the Augmented Dickey-Fuller (ADF) test was applied. Since stock price data often exhibits non-stationary behavior, data differencing was used to achieve stationarity and prepare the data for time series modeling.

**Model Development**

To forecast stock prices, a combination of classical statistical models and deep learning was applied:

**ARIMA** (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) were employed to capture autoregressive and seasonal patterns.

**SARIMA** (Seasonal ARIMA): Extended ARIMA by incorporating seasonal terms to capture repeating seasonal patterns.

**Holt-Winters Exponential Smoothing** was used for trend and seasonality modeling.

**LSTM** (Long Short-Term Memory) neural network was implemented to capture complex nonlinear dependencies in the data.

**Model Evaluation**

Model selection and tuning were guided by analysis of PACF (Partial Autocorrelation Function) and ACF (Autocorrelation Function) plots, which helped in identifying suitable AR and MA terms. The models were compared based on Mean Absolute Percentage Error (MAPE). Among all approaches, the LSTM model achieved the lowest error with a MAPE of 3.78%, making it the best-performing method for forecasting stock prices.

**Results and Insights**

The project demonstrated that while traditional statistical models like ARIMA and Holt-Winters provide interpretable results, LSTM outperformed them in terms of predictive accuracy. The insights highlight the importance of combining both classical and modern approaches when dealing with financial time series data.
