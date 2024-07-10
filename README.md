# Algorithmic trading projects

Index (Classic) is an implementation of a super simple trading strategy using the Quant Connect API. The strategy involves using moving averages to get the direction of price and entering based on certain parameters. Multiple risk management techniques have also been implemented to make sure the strategy is performing at around breakeven. That is really good considering it is a very basic strategy that is difficult to make profitable.

New Algo Testing uses specific functions to generate signals on price data. The functions are rolling windows, directional change, and perceptually important points. Each one is serperatel used to generate points on price data where buys or sells can be taken. Input parameters can be adjusted to change the frequency of points or signals. I used the backtesting.py framework to backtest the function.

