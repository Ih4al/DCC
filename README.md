# Conditional Correlation Analysis between Monero and Bitcoin

This repository contains an R script to analyze the conditional correlations between Monero and Bitcoin prices using the `rmgarch` package. The script models the volatility of Monero and Bitcoin using GARCH models with external regressors and then computes the Dynamic Conditional Correlation (DCC) between the two cryptocurrencies.

## Data

The dataset used in this project should contain the following columns:
- `Mon_P`: Monero prices.
- `Btc_P`: Bitcoin prices.
- `Eth_P`: Ethereum prices.

Ensure your dataset is named `DATA_Updated` and has the columns mentioned above.

## Requirements

The script requires the following R packages:
- `rmgarch`
- `ggplot2`
