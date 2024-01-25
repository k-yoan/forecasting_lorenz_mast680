# Forecasting Chaos with Neural Networks
Academic project (MAST 680/Winter 2023 - Concordia University, Montreal), Professor: Jason J. Bramburger

The goal of this project/assignment was to use neural networks to predict future states of the solutions to some special cases of the Lorenz equations. In particular, the following questions had to be answered:
- what loss function provides the best predictions?
- how far into the future do the predictions remain accurate?
- how good are the predictions for parameter values outside the training data?

Brief summary of the results: the neural network can accurately predict the next state of the system for some values of $\rho$, but only for the first few steps in time.

![plot28](https://github.com/k-yoan/forecasting_lorenz_mast680/assets/69819704/9b1d1580-f44a-481e-b4c0-0a5a01087cfb)
![plot17](https://github.com/k-yoan/forecasting_lorenz_mast680/assets/69819704/f5d5ab1c-d17b-4de5-b935-daae623c2979)
