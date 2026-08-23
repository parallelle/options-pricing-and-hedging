# Option Pricing and Dynamic Hedging

Derivative pricing and hedging models developed as part of undergraduate
Financial Mathematics coursework at The Ohio State University.

## Overview

This project applies mathematical methods for derivative pricing and risk
management using the Black-Scholes-Merton model and binomial option pricing.

The analysis includes option valuation, Greeks, dynamic hedging, and the
comparison of European and American option pricing.

## Black-Scholes-Merton Pricing

Implemented the Black-Scholes-Merton model to calculate theoretical European
call and put option values using inputs including:

- Underlying asset price
- Strike price
- Volatility
- Time to expiration
- Risk-free interest rate

Option sensitivities were evaluated using Delta, Gamma, and Theta.

![Black-Scholes pricing and Greeks](figures/black_scholes_and_greeks.jpg)

## Dynamic Hedging

Constructed a multi-period hedging simulation in which the option was repriced
as the underlying asset price and time to expiration changed.

Delta was recalculated during each period and the underlying stock position was
rebalanced to adjust the hedge.

The analysis also examined Gamma exposure and the use of additional option
positions in managing portfolio risk.

![Dynamic hedging](figures/dynamic_hedging.jpg)

## Binomial Option Pricing

Implemented multi-period binomial models for both European and American options
using risk-neutral valuation.

For American options, exercise and continuation values were compared throughout
the tree to account for the possibility of early exercise.

![Binomial option pricing](figures/binomial_pricing.jpg)

## Tools and Concepts

- Microsoft Excel
- Black-Scholes-Merton model
- Binomial option pricing
- Risk-neutral valuation
- Delta
- Gamma
- Theta
- Dynamic hedging
- Option risk management

## Project Context

This project was completed as part of undergraduate Financial Mathematics
coursework and has been organized here as a portfolio example of applied
mathematical finance.
