# Stock-Price-Prediction

In this project, an ARIMA (AutoRegressive Integrated Moving Average) model was developed to forecast Netflix stock prices for the next 30 days(Dataset from Kaggle). ARIMA models are a popular choice for time series analysis and forecasting.

The ARIMA model was fitted to historical stock price data, specifically the "Adj Close" prices. The order of the ARIMA model was determined by iterating over different combinations of AR (Autoregressive) and MA (Moving Average) parameters. The AIC (Akaike Information Criterion) was used as a measure of model goodness-of-fit and complexity. The model with the lowest AIC was considered the best fit.

Once the ARIMA model was fitted and the optimal parameters were determined, the forecasted values were obtained using the forecast() function. The forecasted values were then plotted on a graph along with the corresponding dates.

The forecasted values provide an estimate of the stock prices for the next 30 days based on the historical data and the patterns captured by the ARIMA model.
