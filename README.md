# Predicting Apple Inc. Stock Prices Using LSTM Model
Objective: Forecast Apple Inc.'s stock prices for 2021 using an LSTM model trained on data from 1980 to 2021.

Data Preparation: Load and preprocess data, scale 'Close' prices with MinMaxScaler, and split into training (80%) and testing sets.
Model Building: Construct an LSTM model with two LSTM layers and dropout for regularization.
Training: Train the model for 75 epochs on the prepared data.
Prediction: Forecast stock prices for 2021 and compare with actual values.
Evaluation: Calculate RMSE to assess model accuracy.
Visualization: Plot actual vs. predicted prices.
Dataset: Historical stock prices from 1980 to 2021 with columns: Date, Open, High, Low, Close, Adj Close, Volume.
