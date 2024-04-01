# Bitcoin Price Forecasting using LSTM
This project utilizes Long Short-Term Memory (LSTM) neural networks to forecast the price of Bitcoin (BTC) based on historical data. LSTM networks are well-suited for sequential data like time series, making them a popular choice for financial forecasting tasks.

# Overview
The project involves the following steps:

### Data Collection: Historical Bitcoin price data is collected from the Yahoo Finance API or any other suitable source.

### Data Preprocessing: The collected data is preprocessed to remove any outliers, missing values, and to scale the data for better model performance.

### Model Building: Two LSTM models are built - a baseline model and an optimized model. The baseline model uses two LSTM layers with 512 and 256 units respectively, while the optimized model uses two LSTM layers with 50 and 100 units. Both models are trained using Adam optimizer and mean squared error loss.

### Model Evaluation: The models are evaluated on a test dataset using Mean Absolute Error (MAE) metric to measure the accuracy of the forecasts.

### Visualization: The results of the forecast are visualized using Matplotlib to compare the predicted prices against the actual prices.

# Dependencies
- Python 3.x
- Libraries: numpy, pandas, scikit-learn, keras, matplotlib
