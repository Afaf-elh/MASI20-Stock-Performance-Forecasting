# MASI 20 Stock Performance Forecasting

## PhD Research Project

**Research topic:** Forecasting the stock market performance of MASI 20 companies using hybrid ARIMA–LSTM approaches.

## Research Objectives

- Analyze the stock market performance of MASI 20 companies.
- Develop and evaluate ARIMA and LSTM models.
- Implement a hybrid ARIMA–LSTM forecasting model.
- Compare hybrid models against baseline models.
- Evaluate 1, 5, and 10 trading-day forecasting horizons.

## Methodology

The research uses daily financial market data and a quantitative forecasting framework.

The proposed hybrid combines:

1. **ARIMA:** Linear time-series modeling.
2. **LSTM:** Nonlinear modeling of ARIMA residuals.
3. **Hybrid:** Combination of both forecasts.

Chronological validation and walk-forward testing will be used to avoid data leakage.

## Project Structure

- `data/raw/`: Original datasets.
- `data/processed/`: Prepared datasets.
- `notebooks/`: Analysis and experiments.
- `src/preprocessing/`: Data preparation.
- `src/models/`: Forecasting algorithms.
- `src/evaluation/`: Model evaluation.
- `results/`: Experimental results.
- `docs/`: Research documentation.

## Status

Research in progress.
