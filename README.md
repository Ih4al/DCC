# Conditional Correlation Analysis between Monero and Bitcoin

This repository contains an R script to analyze the conditional correlations between Monero and Bitcoin prices using the `rmgarch` package. The script models the volatility of Monero and Bitcoin using GARCH models with external regressors and then computes the Dynamic Conditional Correlation (DCC) between the two cryptocurrencies.

## Why?

The script was built for an assignment on Monero. I wanted to run the DCC for Monero and Bitcoin and then for Monero and Ethereum. The problem was that Monero should have three dummies while Bitcoin and Ethereum only one. The program that was used for the assignment, Gretl, wouldn't allow such a thing. Thus, the script was built.  

## Data

The dataset used in this project should contain the following columns:
- `Mon_P`: Monero prices.
- `Btc_P`: Bitcoin prices.
- `Eth_P`: Ethereum prices.


## Requirements

The script requires the following R packages:
- `rmgarch`
- `ggplot2`
