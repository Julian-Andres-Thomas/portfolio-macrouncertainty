# 📈 Multi-Factor Portfolio Construction under Macroeconomic Uncertainty 

This project was developed as the final assignment for the "Python Applied to Portfolio Management" course. It combines macroeconomic reasoning with quantitative finance techniques to build and analyze a defensive investment portfolio.

## 🎯 Objective

Design a portfolio adapted to an environment of increased macroeconomic uncertainty, using both economic reasoning and quantitative methods.

## 📊 Methodology

- **Asset selection**: Focused on sectors with inelastic demand during downturns (healthcare, defense, tobacco, retail).
- **Portfolio optimization**: Return-maximizing optimization with minimum exposure constraints using `cvxpy`.
- **Factor analysis**:
  - Beta vs. S&P 500.
  - Fama-French 3-factor exposure (Mkt-RF, SMB, HML).
  - Regressions on sector factors (Health, Defense, Retail, etc.).
- **Backtesting**:
  - Evaluated performance in bull (2020–2021) and bear (2022) markets.
  - Compared expected (ex-ante) and realized (ex-post) returns and volatilities.
- **Risk modeling**:
  - 95% 1-month Value at Risk (VaR) via Monte Carlo simulation (100,000 simulations).
  - Based on lognormal price dynamics (Black-Scholes assumptions).

## 📈 Key Results

- The portfolio achieved strong resilience in bear markets, with lower volatility than the market.
- Sectoral factor regression showed high correlation with the pharmaceutical sector.
- Monte Carlo VaR indicated a 5% risk of losing more than ~\$52 in 30 days.

## 🛠️ Tools & Libraries

- Python
- `pandas`, `numpy`, `matplotlib`, `cvxpy`, `statsmodels`, `yfinance`

## 🗂️ Files

- `portfolio_analysis.ipynb` – Full Jupyter notebook

## Authors

Julian Andrés & Pablo Domínguez  
May 2025



