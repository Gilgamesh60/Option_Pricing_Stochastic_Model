# Stochastic Modeling for Option Pricing & Stock Markets.

## Introduction :

This is a repo collecting everything I did as a project for the course of course "Stochastic Modeling & its Applications" under Professor Ethayraja Mani of chemical engineering department from Jan-May 2024.
The goal of this project is to understand continuous time stochastic models like GBM and jump diffusion models.We will also perform monte carlo simulation to calculate important statistics parameter Value at Risk (VaR) to predict the worst likely loss for a portfolio given a confidence interval. 


## Stochastic Processes :

A Stochastic process is any process that describes the evolution of a random phenomenon in time. According to the random walk hypothesis in financial theory, stock market prices evolve according to a random walk and thus cannot be predicted. With the efficient-market hypothesis being consistent with the random walk hypothesis, we can therefore try to model different stochastic processes to describe the movement of the SPY for a chosen number of time-steps. In this case, we are going to model three different stochastic processes, mainly used for asset pricing, but that can be extended to explain portfolio behavior and therefore be used as a risk management tool for case scenario analysis.


## Brownian Motion :

Brownian motion, originally used to model the random motion of liquid and gas particles, was introduced by Louis Bachelier in relation to the financial markets to evaluate stock options. Black and Scholes later emphasized some of the properties used by Bachelier to build the Black-Scholes Formula. There is a very good Veritasium youtube video on this exact same thing. He calls this equation the trillion dollor equation which is very fitting. In financial theory, Brownian motion is often described as a Wiener process, where the 0th step has a value of 0, the function of time minus the wiener process at that time is continuous, and the wiener process has independent normally distributed increments.

![The Trillion dollor equation](https://github.com/Gilgamesh60/Option_Pricing_Stochastic_Model/assets/104096164/fb651e00-9791-4f25-a6e4-9ce3bbaaa56c)

Brownian motion is describing that at a given time interval, the current price of the stock will be equal to the previous price multiplied by a random variable (Wiener process). With a statistically coherent number of samples, we will get a normally distributed set of prices with small standard deviations.


## Geometric Brownian Motion : 

To derive the Black Scholes equation, Fisher Black and Myron Scholes presented geometric Brownian motion as a model that contained the Wiener process Z with the addition of a drift module and volatility module. Where geometric Brownian motion explains that the change in an asset price at a predetermined time is equal to the percentage drift expected annually times the current price, plus the daily volatility expected annually in the asset price times the Wiener process.

I used this paper to understand and implement this model :
[https://www.columbia.edu/~ks20/FE-Notes/4700-07-Notes-BM.pdf](https://www.columbia.edu/~ks20/FE-Notes/4700-07-Notes-BM.pdf)








