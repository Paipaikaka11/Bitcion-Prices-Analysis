# Bitcoin Prices Analysis (R)

Statistical analysis of factors associated with **Bitcoin (BTC) price** using **linear regression in R**, with exploratory plots and model diagnostics. Inputs include crypto prices (BTC/ETH/XRP), market activity (volume, transactions), macro/alt assets (VIX, MSCI World, Gold), and miner metrics.

---

## 📂 Repository Structure

* `STA302 Final Project.Rmd` — main R Markdown with the full analysis, figures, and model results.
* `*.csv` — input datasets (BTC price, ETH price, miner revenue, exchange volume, VIX, MSCI World, gold, tx volume, supply).
* `README.md` — project overview (this file).

---

## 🧠 What this project does

* Cleans and merges raw CSVs into a modeling dataset.
* Explores relationships (correlations, trend/volatility plots).
* Fits **multiple linear regression** to explain BTC price using fundamental/market features.
* Evaluates model with standard diagnostics (R²/Adj-R², residuals, multicollinearity checks).
* Interprets coefficients to discuss **which factors matter most** for BTC price.
  (Original README states the aim is to analyze factors affecting BTC price via linear regression.

---

## 🛠 Tech Stack

* **R**, **R Markdown** (`.Rmd`)
* Suggested packages: `tidyverse`, `lubridate`, `readr`, `ggplot2`, `broom`, `car`, `performance`

---

## 📊 Inputs

* `Bitcoin Price.csv`, `ETH price.csv`, `Ripple (XRP) price.csv`
* `Exchange volume.csv`, `transaction volume.csv`
* `Volatility index.csv`, `MSCI World Historical Data.csv`, `Gold Price.csv`
* `Bitcoin Miner revenue.csv`, `number of bitcoin.csv` 


