# Black Scholes and Greeks

**Black-Scholes Model**

In the Black-Scholes model, the stock price follows a Geometric Brownian motion
$$dS_t = \mu \, S_t \, dt + \sigma \, S_t \, dW_t,$$
where $\mu$ is the drift coefficient and $\sigma^2$ corresponds to the volatility. \
\
\
**Greeks and Delta-Hedging**

The Greeks give the sensitivity of the price of derivatives to a change in different parameters. They help to quantify the risk. In this notebook, we implement the Greeks for a Call and Put Option.

We also implement Delta-Hedging, the Delta of an option $V$ is given by
$$\Delta = \frac{\partial V}{\partial S}$$
where $S$ is the stock price. At each step we caluclate the Delta and buy/sell the given amount of shares so that the portfolio's Delta is zero

![image](https://github.com/alexisdpc/Black-Scholes-and-Greeks/assets/124795834/13b9e5cb-d120-4294-8a57-63a870ce44a7)

