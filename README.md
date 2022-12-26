# Data-driven-approaches
This project's objective is to predict asset price movements on the horizon of 60 seconds for high frequency trading. 

## Data
L1+L2 data by seconds, consisting of 5 levels of an order book + aggregated data on what happened during each second:
ask_price_i, bid_price_i, ask_quantity_i, bid_quantity_i, trade_price, trade_quantity divided by buy and sell.

## Current progress
Two solutions have been created: a baseline linear legression on all non nan features and an ARIMA (autoregressive integrated moving average) model.

## Future plans:
### ARIMA
More frequent updates, which provide a great boost to perfomance, but are currently unimplemented due to time limitations of testing system, despite taking 0.003 s per prediction locally.

### Linear regression
Regularization

### Ordering:
Trading simulation implementing PnL metric, transaction costs.

