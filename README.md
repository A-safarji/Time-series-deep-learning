# Stock Price Prediction Using Time Series (Deep Learning)

[![License](https://img.shields.io/badge/license-MIT-brightgreen)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.6+-blue?logo=python)](https://www.python.org/)
[![PRsWelcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white
)](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white
)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white
)



* Univariate Time Series

Predicting stock price using historical data of a company using Neural Networks for multi-step forecasting of stock price.

# General info
This project is; to implement deep learning algorithms two sequential models of recurrent neural networks (RNNs) such as stacked LSTM, Bidirectional LSTM, and NeuralProphet built with PyTorch to predict stock prices using time series forecasting.

## Table of contents
* [What is Time Series?](#project-info)
* [What is LSTM?](#)
* [What is Bidirectional LSTM?](#)
* [What is NeuralProphet?](#)
* [Started With the Stock Data](#)
* [Model Implementation Phase](#)
* [Models Train & validation Loss](#)
* [Conclusion](#)

### This project was created for the article: Univariate Time Series With Stacked LSTM, BiLSTM, and NeuralProphet.
- [From here to read the table of contents](https://pub.towardsai.net/univariate-time-series-with-stacked-lstm-bilstm-and-neuralprophet-c8d6a11a9665)
 
# Stock Data
Data are obtained from 2010–01–04 to 2021–11–02 (11 years, 9 months, and 29 days) for Apple Inc (AAPL) and exported directly from Yahoo finance. Stock price history will be for the past 11 years (including the Covid-19 period). 
* Use Yahoo Finance API to grab stock data.
* [More about data descrption from here](https://github.com/A-safarji/Time-series-deep-learning/tree/main/Date)

# Visualising Results 

* Stacked LSTM 
<img width="753" alt="Screen Shot 2022-01-02 at 9 13 34 PM" src="https://user-images.githubusercontent.com/20365333/147885282-9f25b258-b95e-4f84-8eb7-66bbd2dafcf4.png">

* Bidirectional LSTM

<img width="717" alt="Screen Shot 2022-01-02 at 9 12 42 PM" src="https://user-images.githubusercontent.com/20365333/147885260-07708e2e-ab3f-4516-a3cf-01a7ff189520.png">


* NeuralProphet

<img width="735" alt="Screen Shot 2022-01-02 at 9 10 23 PM" src="https://user-images.githubusercontent.com/20365333/147885217-e0d2dfd0-7ca2-478f-b554-67e165deaad6.png">


# Technologies
* [Colab](https://colab.research.google.com/notebooks/)
* [numpy](http://www.numpy.org/)  
* [pandas](https://pandas.pydata.org/)  
* [sklearn](http://scikit-learn.org/stable/)  
* [scipy](https://www.scipy.org/)  
* [matplotlib](https://matplotlib.org/)  
* [tensorflow](https://www.tensorflow.org/)  
* [keras](https://keras.io/)  
* [Plotly](https://plotly-r.com/)
* [NeuralProphet](https://neuralprophet.com/html/contents.html)
* [h5py](http://docs.h5py.org/en/latest/build.html)
* [Facebook Prophet](https://pypi.org/project/prophet/) (Included to the project)


# Final thoughts
The analysis of using three deep learning algorithms shows that they remain a worthy investment for the future. A qualified investor, on the other hand, should perform both external and internal business research before making an investment decision in order to obtain a full picture of the company's potential value.

------------
# Disclaimer
Attempts have been made to predict stock prices using time series analysis algorithms, but they are not yet available for betting in the real market. This is just a tutorial and implementation of deep learning models to forecast stock. Therefore, it is not intended to instruct people to buy stock from this repo.

## Contributing
>You can check out the full contribution document [here](https://github.com/A-safarji/Time-series-deep-learning/blob/main/CONTRIBUTING.md)
- Fork the Repository [here](https://github.com/A-safarji/Time-series-deep-learning.git)

1- [Fork it](https://github.com/A-safarji/Time-series-deep-learning.git)

2- Create your feature branch (git checkout -b feature/fooBar)

3- Commit your changes (git commit -am 'Add some fooBar')

4- Push to the branch (git push origin feature/fooBar)

5- Create a new Pull Request


## Contact

[Stock Price Prediction Using Deep Learning](https://github.com/A-safarji) - feel free to contact!
