# Final-Year-Project-Time-Series-Forecasting

About The Project

The accurate prediction of stock prices has always been a challenging task due to the dynamic and volatile nature of financial markets. In this project, we aim to develop a robust forecasting model using Long Short-Term Memory (LSTM) and Autoregressive Integrated Moving Average (ARIMA) algorithms for time series analysis of stock prices.
The objective of this study is to compare the performance of LSTM and ARIMA models in predicting stock prices and identify their strengths and limitations. The LSTM model, a type of recurrent neural network (RNN), excels in capturing long-term dependencies and patterns in sequential data. On the other hand, ARIMA, a traditional statistical model, is effective in capturing short-term trends and stationary components

# key words.

Time Series Forecasting, stock prices, LSTM, ARIMA, recurrent neural network, forecasting accuracy.

# Code

![Screenshot (35)](https://github.com/DLalithB/Final-Year-Project-Time-Series-Forecasting/assets/102012487/9cc48959-31d1-485c-a765-3c3fc49053ee)

# Dashboard

![Algorithm menu](https://github.com/DLalithB/Final-Year-Project-Time-Series-Forecasting/assets/102012487/8b7937fb-a21f-48f8-901a-ce73e1ecd9db)

# prediction result

![prediction result](https://github.com/DLalithB/Final-Year-Project-Time-Series-Forecasting/assets/102012487/2c63cc9d-de28-4361-9ff7-58466dbe9e9e)

# Built with 

        .Python
        
        .Flask
        
        .Tensorflow
        
        .Keras
        
# Module Algorithm

        ARIMA

        LSTM_model

# Install python packages

        pip install matplotlib

        pip install sklearn

        pip install flask

        pip install KNN

# Usage

        This program predicts the price of GOOG stock for a specific day using the Machine Learning algorithm called Support Vector Regression (SVR) Linear Regression. Importing flask module in the project is mandatory An object of Flask class is our WSGI application.

# Contents

       app.py

       GOOG_30_days.csv

        train_models.py

        utils.py

        GOOG_30_days.csv

# Table for dataset pre-processing

 | Files  | Content | Stage Deliverable |
| ------------- | ------------- | ------------- |
| data.csv  | Raw stock price data in CSV format|Data Collection  |
| preprocessed_data.csv  | Pre-processed stock price data|Data Pre-processing  |
| train.csv  | Training data split from pre-processed data  |Data Splitting  |
| test.csv| Testing data split from pre-processed data  |Data Splitting |
| model.h5  | Trained LSTM model for stock price forecasting  |Model Training  |
|predictions.csv  | Predicted stock prices on the testing data |Model Prediction  |
| evaluation.csv| Evaluation metrics calculated for predictions  |Model Evaluation  |
