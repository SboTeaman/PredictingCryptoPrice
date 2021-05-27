# Predicting Cryptocurrency price.
* General info
* Screenshots
* Technologies
* Features
* Code sample
* Status

## General info
This program predicts the price of cryptocurrencies using **Neutral network**.
## Screenshots
  ![Image of the game](https://raw.githubusercontent.com/SboTeaman/PredictingCryptoPrice/master/prediction.png?token=AOVS2YJNBWBQF6W7K7ZLP4DAWAT54)
 
 *This is result prediction plot*
## Technologies
Language: 
* Python
  
Libraries:
* numpy 
* matplotlib
* pandas 
* pandas_datareader 
* sklearn
* tensorflow

  
## Features
* You can select cryptocurrency to predict.
* You can select currency.
* You can adjust how many days you enter into the test data.


## Code sample
```
test_start =dt.datetime(2016, 1, 1)
test_end = dt.datetime.now()

test_data = web.DataReader(f'{crypto_currency}-{against_currency}', 'yahoo', test_start, test_end)
actual_prices = test_data['Close'].values
 ``` 
## Status
Project is: *in progress*.
