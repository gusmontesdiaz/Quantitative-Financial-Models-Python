# Quantitative Financial Models: Forecasting, Valuation, and Risk (VaR)

## 🎯 Project Objective

This project serves as a comprehensive demonstration of advanced quantitative modeling techniques used in finance and actuarial science. It covers three distinct, mission-critical applications: asset price forecasting, derivatives valuation, and market risk measurement. The goal is to provide robust, coded solutions that go beyond standard spreadsheet analysis.

## 🛠️ Key Technologies and Libraries

The entire analysis was implemented in a Python environment (Jupyter Notebook) leveraging industry-standard libraries:

* **`pandas` and `numpy`**: For data manipulation, numerical calculation, and efficient simulation.
* **`yfinance`**: Used for automated extraction of historical market data (AAPL, MXN=X, GFNORTEO.MX).
* **`scipy.stats.binom`**: Implemented for the binomial distribution probability mass function required in the Cox-Ross-Rubinstein option pricing model.
* **`matplotlib`**: Utilized for the visualization of the Profit & Loss distribution in the VaR calculation.

## 📊 Core Models and Methodologies

This notebook features three separate quantitative models:

### 1. Asset Price Forecasting (Wiener Process / Geometric Brownian Motion)
* **Objective:** To simulate and forecast the future price of Apple stock (`AAPL`) using Monte Carlo simulation.
* **Methodology:** Implementation of the **Wiener Process** (Geometric Brownian Motion) to model asset paths, incorporating historical volatility and drift derived from real market data.

### 2. Derivatives Valuation (Cox-Ross-Rubinstein Binomial Tree)
* **Objective:** To calculate the fair theoretical price of European CALL and PUT options on the Mexican Peso (`MXN=X`).
* **Methodology:** The **Cox-Ross-Rubinstein (CRR) Binomial Model** is constructed, calculating risk-neutral probabilities and discount factors to value the options.

### 3. Market Risk Measurement (Historical Value at Risk - VaR)
* **Objective:** To quantify the potential maximum loss over a specific time horizon for a financial asset (`GFNORTEO.MX`).
* **Methodology:** **Historical Simulation VaR** is calculated at 90%, 95%, and 99% confidence levels, based on the distribution of historical Profit & Loss (P&L).

## ✨ Value Proposition for the Analyst Role

* **Risk Modeling Expertise:** Proven ability to calculate and interpret critical risk metrics (VaR) using a rigorous historical simulation approach.
* **Advanced Quantitative Skills:** Direct experience in pricing complex financial products (derivatives) using recognized industry models (CRR).
* **Data-Driven Forecasting:** Competence in utilizing stochastic processes (Wiener/GBM) for forward-looking projections, essential for reserving and planning.
