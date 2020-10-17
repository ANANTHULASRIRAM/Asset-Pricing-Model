# Asset-Pricing-Model
A comparative analysis of the option pricing using Black-Scholes partial differential equation and Monte Carlo simulations using discretized version of Geometric Brownian Motion (GBM)

The value of a European call or put option for a non-dividend-paying underlying stock is given by
the solution of the Black-Scholes equation. Alternatively, a option price of an underlying stock can be modeled by Monte Carlo simulations using
Geometric Brownian Motion (GBM) with constant drift and volatility. The discretized version
of GBM is known as Geometric Random Walk equation. 

In this project, I have obtained the prices of the European option from Monte Carlo simulations by computing call and put
payoffs and discounting those back to current time with the riskless short rate. Analysis was made by choosing different number of time steps when computing the price of an option.
