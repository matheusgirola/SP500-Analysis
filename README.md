# SP500-Analysis
Experiments with SP500 data using Python

This repository contains a series of notebooks with different approachs in analysing and forecasting SP500 index data. This project as whole is still in development, and some notebooks are more well elaborated and organized than others. We can summarize each one as follows:

* SP500 Alieen Nielsen (heavily in development): is a replica from Alieen Nielsen's Book "Pratical Time Series Analysis" for studies and reference purpose. 
* SP500 closing price ARIMA-GARCH (finished: In revision phase): here, I try to fit an ARIMA-GARCH into the closing price, a standard approach in the literature;
* SP500 log ARIMA-GARCH (almost finished): the same as the notebook above, but with logged series;
* SP500 with ML (in development): Here I used the returns of SP500 insted of closing price, together with a diversity of models to experiment fitting the data. At this point, I used the following models: Hidden Markov Process; Moving Average; Linear Regression; K-nearest neighbours; Prophet; and LSTM.
