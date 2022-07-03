# Tesla_Project



Ultimately, the goal of active investment management is to generate Alpha, defined as  when investment managers say “our goal is to generate alpha,” they are basically saying that the goal is to generate a higher return while assuming a similar amount of risk as compared to the benchmark against which they measure their performance. portfolio returns in excess of the benchmark used for evaluation. The fundamental law of active management postulates that the key to generating alpha is having accurate return forecasts combined with the ability to act on these forecasts (Grinold 1989; Grinold and Kahn 2000).

It defines the information ratio (IR) to express the value of active management as the ratio of the return difference between the portfolio and a benchmark to the volatility of those returns. It further approximates the IR as the product of

The information coefficient (IC), which measures the quality of forecast as their rank correlation with the outcomes
The square root of the breadth of a strategy expressed as the number of independent bets on these forecasts


Im not really sure how i am going to do it, but with my market experience I am going to make something and develop a viable product



# Finally, an original project



# Some Data Dictionary Items Gen Stuff to know about investing, it would behoove you to learn this stuff ! Also some forecast quality metrics Before we begin forecasting, let's understand how to measure the quality of our predictions and take a look at the most commonly used metrics.

- Simple Moving Average (SMA): Average of the price of stock for a set period of time, in our case we have used a simple moving average of 5,10,15 and 30 days.

- Exponential Moving Average (EMA): An exponential moving average (EMA) is a type of moving average (MA) that places a greater weight and significance on the most recent data points, basically what it means is that the newer stock price data has a higher weightage/significance on the price than older days.

- Relative Strength Index (RSI): A momentum indicator used in technical analysis that measures the magnitude of recent price changes to evaluate overbought or oversold conditions in the price of a stock.

- Moving average convergence divergence (MACD) is a trend-following momentum indicator that shows the relationship between two moving averages of a security’s price. The MACD is calculated by subtracting the 26-period exponential moving average (EMA) from the 12-period EMA. Similar to RSI, MACD triggers technical signals when it crosses above (to buy) or below (to sell) its signal line.



- R squared: coefficient of determination (in econometrics, this can be interpreted as the percentage of variance explained by the model), (−∞,1]

- Mean Absolute Error: this is an interpretable metric because it has the same unit of measurment as the initial series, [0,+∞)

- Median Absolute Error: again, an interpretable metric that is particularly interesting because it is robust to outliers, [0,+∞)

- Mean Squared Error: the most commonly used metric that gives a higher penalty to large errors and vice versa, [0,+∞)

- Mean Squared Logarithmic Error: practically, this is the same as MSE, but we take the logarithm of the series. As a result, we give more weight to small mistakes as well. This is usually used when the data has exponential trends, [0,+∞)

- Mean Absolute Percentage Error: this is the same as MAE but is computed as a percentage, which is very convenient when you want to explain the quality of       the model to management, [0,+∞)



# Also, for you History buffs it is time to meet the Greeks !!
I will introduce my friends ---->


Delta, I help you gauge the likelihood an option will expire in-the-money (ITM), meaning its strike price is below (for calls) or above (for puts) the underlying security’s market price.



Gamma, I can help you estimate how much the Delta might change if the stock price changes.



Theta, I can help you measure how much value an option might lose each day as it approaches expiration.



Vega, I can help you understand how sensitive an option might be to large price swings in the underlying stock.




Rho, I can help you simulate the effect of interest rate changes on an option.


## We are the Greeks, "nice to meet you !".


