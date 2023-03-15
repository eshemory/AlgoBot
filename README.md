# AlgoBot

Summary: 

This project is a trading algorithm called "ProfitProphet" which trades the S&P 500 ETF (SPY) using technical indicators to determine buy and sell signals. The algorithm uses a 50-day moving average and a 200-day moving average as well as the Relative Strength Index (RSI) indicator to generate trading signals.

The algorithm also implements a trailing stop loss strategy that updates the stop price to 90% of the current asset price if the SPY price hits a new high. The stop price is updated to the higher of the previous stop price and 90% of the current asset price if there is an existing stop market order.

The algorithm had a return of 163.36% during the backtesting period from January 1, 2000 to March 14, 2022.

More specifically, this code defines a trading algorithm that uses technical analysis to buy and sell a single asset, the SPDR S&P 500 ETF (SPY), based on its 50-day and 200-day moving averages and the relative strength index (RSI) indicator. The algorithm also implements a trailing stop-loss strategy, which is updated when the price of SPY reaches a new high. During the backtest period from January 1, 2010 to March 14, 2022, the algorithm buys 200 shares of SPY when the fast moving average crosses above the slow moving average and the RSI is below 50, and sells all holdings when the fast moving average crosses below the slow moving average or the RSI is above 70. The algorithm also places a stop-loss order at 90% of the highest price of SPY seen so far, and updates the stop-loss order as the price of SPY increases. The algorithm visualizes the price of SPY and the stop-loss order on a chart.
