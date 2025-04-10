# Advanced-Research-Time-Series-Modelling-Case-Study
This Code seeks to analyze the time series data using statistical and deep learning techniques for Johnson and Johnson’s quarterly sales and Amazon’s closing stock prices per month.
an RNN with LSTM layers is built. Before the implementation of the sequences, the data is scaled using the MinMaxScaler engine and the sequence is prepared using sliding windows.
The LSTM model constructs the next 24 time steps from previous data which are used to train it. For the evaluation of the two models, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²) are used as means of assessment. This way, the screening and classification can be done using both statistical and deep-
learning-based models for comparisons.
