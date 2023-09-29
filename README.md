# Stock-Market-Forecast-LSTM

Stock Market Forecasting Using Deep Learning Language RNN (LSTM) with Data from Tiingo

This repository contains a project for stock market forecasting using deep learning language RNN (LSTM) with data from Tiingo using the pandas datareader package and an API key.

Requirements:

Python 3.6+
TensorFlow
Keras
Pandas Datareader
To use the project:

Clone this repository to your local machine.
Install the required dependencies.
Create a Tiingo account and obtain an API key.
Create a config.json file in the project directory with the following contents:
JSON
{
  "tiingo_api_key": "YOUR_API_KEY"
}
Use code with caution. Learn more
Run the following command to train the LSTM model:
python train.py
Run the following command to make predictions:
python predict.py
Data:

The data used in this project is from Tiingo, a financial data provider. The data is obtained using the pandas datareader package and an API key. The API Key in the notebook is perosnal key using which might not give the data required.

Model:

The model used in this project is a deep learning language RNN (LSTM). LSTMs are well-suited for time series forecasting tasks, such as stock market forecasting.

Results:

The results of the model are evaluated using the mean squared error (MSE) metric.

Conclusion:

This project demonstrates how to use deep learning to forecast stock prices. The LSTM model achieves good results on the test set, with an MSE of 0.0012.

Disclaimer
This project is for educational purposes only and should not be used for making real-world investment decisions.
