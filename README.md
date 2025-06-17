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


Buenísimo, Julian. Acá te dejo la **checklist definitiva de Excel para un perfil como el tuyo (quant analyst con base técnica)**. Esto **no es lo típico de "sumas y restas"**, sino lo que realmente importa si ya sabés Python y querés que Excel te sirva de apoyo, presentación o incluso validación.

---

## ✅ **Checklist de Excel para Quants (y futuros)**

### 📈 1. **Funciones estadísticas clave**

* `AVERAGE()`, `VAR.P()`, `STDEV.P()` — (media, varianza, desviación estándar)
* `NORM.DIST()`, `NORM.INV()` — distribución normal
* `T.DIST()`, `CHISQ.DIST()` — distribuciones de prueba
* `PERCENTILE()`, `QUARTILE()`, `RANK()` — análisis de percentiles
* `CORREL()`, `COVARIANCE.P()` — correlación y covarianza

### 🔢 2. **Análisis de datos (con el Toolpak)**

* Activá el *Data Analysis Toolpak* y practicá:

  * Regresiones lineales
  * Histogramas
  * Análisis descriptivo
  * Pruebas de hipótesis

### 📊 3. **Gráficos que sirven de verdad**

* Líneas, áreas y barras con diseño limpio (no esos colorinches por defecto).
* Scatter plot con líneas de tendencia (para mostrar correlaciones o ajustes).
* Gráficos dinámicos con segmentación o controladores (slicers).

### 📑 4. **Tablas dinámicas (Pivot Tables)**

* Filtrar, resumir y agrupar grandes datasets.
* Aplicar funciones estadísticas dentro de la tabla.
* Conectar con gráficos dinámicos.

### 💡 5. **Funciones lógicas y de búsqueda**

* `IF()`, `AND()`, `OR()` — para crear condiciones
* `VLOOKUP()`, `HLOOKUP()` → básicos
* `INDEX() + MATCH()` → más potentes y flexibles que los anteriores

### 🎲 6. **Simulaciones tipo Monte Carlo**

* Usá `RAND()` y `NORM.INV(RAND(), media, desviación)` para generar escenarios.
* Simulá portafolios, precios, o escenarios de riesgo.
* Calculá métricas sobre cada simulación: retorno esperado, VaR, CVaR (de forma simplificada).

### 🧮 7. **Solver: Optimización en Excel**

* Hacé:

  * Minimizar CVaR (si lo simplificás con percentiles)
  * Maximizar Sharpe ratio
  * Aplicar restricciones de peso
* Simulá el trabajo de tu optimizador de Python pero en entorno visual.

### 📥 8. **Importación y limpieza de datos**

* Importar CSV, datos desde web o bases de datos.
* Usar `TEXT TO COLUMNS`, filtros avanzados, eliminar duplicados.
* Formatos condicionales para detectar outliers, errores, etc.

---


