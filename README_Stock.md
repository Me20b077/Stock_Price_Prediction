# About the data:

The stock market refers to the collection of markets and exchanges where regular activities of buying, selling, and issuance of shares of publicly-held companies take place. Such financial activities are conducted through institutionalized formal exchanges or over-the-counter (OTC) marketplaces which operate under a defined set of regulations. There can be multiple stock trading venues in a country or a region which allow transactions in stocks and other forms of securities. 
## Columns

- **Date**: Date when the stock is up for trade.
- **Open**: Price of the stock when the market opens in the morning.
- **High**: Highest price of the stock throughout the day. 
- **Low**: Lowest price of the stock throughout the day.
- **Close**: Price of the stock when the market closed in the evening
- **Volume**: Quantity of the stock.
- **Stock Trading**: Amount of trading happend on one stock.


**GOAL**
The goal is to predict the price of stocks in future and make calls according to the results algorithms gave.


**WHAT I HAD DONE**
- I have explored the data of given stocks
- Make models according to data to predict the price of the stock.
- I have plotted the results of the prediction.

**MODELS USED**
-  Moving Average
-  Linear Regression
-  K-Nearest Neighbors
-  Prophet
-  LSTM

**LIBRARIES NEEDED**
- numpy
- pandas
- matplotlib
- scikit-learn
- Keras

**CONCLUSION**
Accuracy of all models are evaluated throught root mean squared error

By using Moving Average I got 
 ```python
    Accuracy:   14541.48874451343
 ``` 

By using Linear Regression I got 
 ```python
    Accuracy:   20137.79584837273
 ``` 

 By using K-nearest neighbors I got 
 ```python
    Accuracy:   10188.724396928814
 ``` 
By using Prophet I got 
 ```python
    Accuracy:   22307.770208873226
 ``` 
By using LSTM I got 
 ```python
    Accuracy:   2330.171022728133
 ``` 

