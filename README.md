# Portfolio Construction under Macroeconomic Uncertainty 

This project combines macroeconomic reasoning with quantitative finance techniques to build and analyze a defensive investment portfolio.

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
  - 95% confidence level 1-month Value at Risk via Monte Carlo simulation (100,000 simulations).

## 📈 Key Results

- The portfolio achieved 42% return in bull market and 23% return in bear market.
- Sectoral factor regression showed strong and statistically significant relationship with the pharmaceutical sector.
- Monte Carlo VaR indicates a 5% probability of losing more than 1.7% of the porfolio's value over 1 month horizon.

## 🛠️ Tools & Libraries

- Python
- `pandas`, `numpy`, `matplotlib`, `cvxpy`, `statsmodels`, `yfinance`

## 🗂️ Files

- `portfolio_analysis.ipynb` – Full Jupyter notebook

## Authors

Julian Andres Thomas & Pablo Domínguez  
May 2025

