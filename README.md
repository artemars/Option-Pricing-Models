# Binomial and Monte Carlo option pricing 
## Overview
In this notebook, I begin by pricing European-style options using the binomial model, assuming no dividend yield. Initially, I allow the user to input the scaling for the "up" movement of the asset price. The "down" movement, however, is constrained to the inverse of the "up" (UD = 1).

Next, I create a similar function, but this time implementing the Cox-Ross-Rubinstein model, setting a large default value for the time steps to improve convergence to the Black-Scholes model. 

Following this, I price American-style options, allowing the input of a continuous dividend yield, again using the Cox-Ross-Rubinstein model. 

Finally, I move on to pricing exotic options, employing the binomial tree approach for path-independent exotics and the Monte Carlo method for path-dependent ones, assuming a log-normal distribution for the asset price.
