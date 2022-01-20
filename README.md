# Group 1 - Project 2

**Group Member:** 

- Alex Amon

- Clarie Stokes

- Sam Kohnle

- Sylvia Fan


## Project Topic: Stock Price Prediction Using Different Machine Learning Models

In this project, we will build and train 5 different models: LSTM, GRU, KNN, SVR and RFR, using a 10 day window of closing prices to predict the 11th day closing price. We will compare the models and analyze the models' performance at predicting stock closing price. 

### Libraries:

**Import libraries and packages: ** 

- numpy 
- os
- math
- pathlib  
- alpaca_trade_api
- hvplot
- sklearn
- tensorflow 
- plotly

### Jupyter Notebook Table Content

\- Import libraries and packages

-Data Loading Method: Using Aplpaca to pull the stock data

\- Preprocessing data

​      \- Checking Null/NA value and remove it

​     \- Converting Date column from string to datetime format

  \- Plotting stock close price chart

  \- Normalizing/scaling close values between 0 to 1

  \- Split data for training and testing keeping date and historical price data in order

\- **Algorithms** 

  \- K-nearest neighbour - KNN

  \- Super vector regressor - SVR

 \-  Long Short Term Memory -  LSTM 

 \- Gated Recurrent Units - GRU

 \-  Random Forest Regressor - RF

\- **Plotting Predicted Close Price of All 5 Models VS Original Close Price **

-**Model Output Metrics Comparison**

​    \- RMSE, MSE and MAE

​    \- Explained variance regression score

​    \- R<sup>2</sup> score for regression

## Project Summary and Findings Presentation:

https://docs.google.com/presentation/d/1Qw0rOhCKXzTHjujHn8pkIDyOwvBNbp-vYXNM_48FbLM/edit#slide=id.p

## Acknowledgements

We would like to first acknowledge the guidance and teaching of our FinTech Boot Camp Instructor, Garth Mortensen, our TA, Roberto Salazar.
