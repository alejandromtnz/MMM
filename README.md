# MMM — Media Mix Modeling and Campaign Prediction

**Media Mix Modeling (MMM)** project: a statistical approach to measure the impact
of different marketing channels on sales/conversions. It combines **SARIMA** time
-series modelling with **optimisation** techniques to analyse campaign data and
predict and improve future performance.

## Overview

The project evaluates the effectiveness of different advertising media and
predicts the expected return under different budget allocations, using
statistical modelling and forecasting tools.

## Repository structure

```
.
├── sarima.ipynb                 # SARIMA model for the time series
├── optimizacion.ipynb           # Optimal media-mix allocation via decision trees (black-box version)
├── optimizacion_regresion.ipynb # Optimal media-mix allocation via linear regression (improved version) + validation
├── datos_combinados.csv         # Consolidated dataset (marketing metrics and results)
└── README.md
```

## Tech stack

Python (pmdarima, statsmodels, pandas, numpy) · SARIMA (Seasonal ARIMA) ·
non-linear optimisation

## Goal

Assess the efficiency of each advertising medium and predict the expected return
for different budget allocations, combining statistical modelling with
optimisation.

## Usage

```bash
jupyter lab
```

Run `sarima.ipynb` for the time-series model, then `optimizacion.ipynb` /
`optimizacion_regresion.ipynb` for the budget-allocation analysis.

---

> **Note:** notebook comments are written in Spanish.
