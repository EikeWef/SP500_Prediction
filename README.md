#Predicting the S&P500 using a recurrent neural network

In this project we applied machine learning on the time-series daily level data of the S&P500 from 1963 - 2019. The project can be divided into 3 main parts:

### Exploratory Data Analysis on Stylized Facts of Asset Returns

We examined the daily returns of the S&P500 with respect to stylized facts of asset returns. This includes an analysis on the distribution: Are they normally distributed? Skewed? Leptokurtic? Additionally, we examined volatility clustering and autocorrelations.

### Building a recurrent neural network (RNN) to predict the level of the S&P500

We built an RNN with a Long Short-Term Memory (LSTM) architecture using scikit-learn and keras (running on the TensorFlow backend). We trained the model, predicted the test data and evaluated the performance.

### Building a feedforward deep neural network (DNN) to compare it with the LSTM model

In order to examine whether the LSTM is actually a good choice when working with time-series data, we also built a feedforward deep neural network using the same libraries. We trained and tested it.

The results of our analysis can be seen in the notebook provided in this repository.

If you have any comments or recommendations for improvement, please feel free to reach out.
