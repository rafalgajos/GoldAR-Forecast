# GoldAR-Forecast

Gold Price Forecasting with Autoregression (Time Series Analysis)

<p>
  <img src="https://pixabay.com/get/g514711c9217e44d37a211845146cc0ecc9f224002d2de0e8c5b1072dd383d0ff53a4d7da4f1f735bdd987e4f2c57906c1c4bfbdaaf3e3b9d91eba1af8fc40bcf114cfb4fc85c28dd2bb04fc4c842bb1f_1280.jpg" width="350" alt="gold bar image">
</p>

## Context

Gold, a valuable and lustrous metal, has fascinated humanity for centuries. It has been used for various purposes, including jewelry and investment. Gold is globally traded on commodity exchanges. The gold price prediction will be based on autoregression.

## Autoregression

A time series is a sequence of measurements of the same variable(s) made over time. Usually, the measurements are made at evenly spaced times - for example, monthly or yearly. Let us first consider the problem in which we have a y-variable measured as a time series.
In this context, we might have **_y_** a measure of the gold price, with measurements observed every 3 months. To emphasize that we have measured values over time, we use **_t_** as a subscript rather than the usual "**i**," i.e., means **_y_** measured in time period **_t_**. The $\epsilon$ is the error term (typically normally distributed). [1]

An autoregressive model is when a value from a time series is regressed on previous values from that same time series. for example,
$y_{t}$ on $y_{t-1}$ [1]:

$y_t = \beta_0 + \beta_{1} y_{t-1} + \epsilon_t$

## Data

Data from Kaggle with a CC0 licence. [2]

File CSV has 10788 rows, and the last date is 2020-03-13.

## Implementation

The implementation of gold price forecasting is done in a Jupyter Notebook.

Sources:

1. The Pennsylvania State University, "Autoregressive Models", T.2.1, https://online.stat.psu.edu/stat501/book/export/html/996
2. Möbius, "Learn Time Series Forecasting From Gold Price", https://www.kaggle.com/datasets/arashnic/learn-time-series-forecasting-from-gold-price
3. Photo by PublicDomainPictures: https://pixabay.com/photos/gold-bars-wealth-finance-gold-bars-163519/
