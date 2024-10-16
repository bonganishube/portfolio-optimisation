# Portfolio Optimisation

## Overview

This Jupyter Notebook project focuses on constructing and optimizing two investment portfolios with an initial capital of $100,000, each containing four stocks. The first portfolio features equal weighting, while the second utilizes optimization to maximize returns adjusted for risk.

## Objectives

- Import five years of historical data for four stocks.
- Create an equal-weighted portfolio.
- Analyze and visualize the equal-weighted portfolio's performance.
- Generate 10,000 portfolio scenarios with random weightings.
- Identify the optimal portfolio based on the highest Sharpe ratio.

## Contents

1. **Import Packages**: Load necessary libraries.
2. **Connect to Data**: Download adjusted closing prices for selected stocks.
3. **Create Equal-Weighted Portfolio**: Calculate normalized returns, allocations, and position values.
4. **Visualize Performance**: Generate line charts for portfolio and stock performance.
5. **Calculate Metrics**: Compute cumulative return, mean daily return, standard deviation, and Sharpe ratios.
6. **Prepare Scenarios**: Set up data structures for portfolio simulations.
7. **Run Scenarios**: Generate 10,000 random weight allocations and calculate returns and risks.
8. **Identify Optimal Portfolio**: Find the configuration with the highest Sharpe ratio.
9. **Visualize Results**: Scatter plots to illustrate risk-return relationships.

## Getting Started

### Prerequisites

Install required packages:

```bash
pip install pandas numpy yfinance matplotlib
