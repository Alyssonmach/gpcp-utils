# GPCP Utilities

Examples and study materials for Production Management, Planning and Control (GPCP), covering demand forecasting, safety stock, and linear programming.

## Contents

- `demand-forecast-Python/` — Jupyter notebook with demand forecasting methods, including moving averages, exponential smoothing, trend projection, seasonal decomposition, and forecast error measures.
- `demand-forecast-R/` — R scripts demonstrating time-series decomposition, moving averages, linear regression, and ARIMA forecasting.
- `safety-stock-R/` — R example calculating safety stock from forecast errors for a 90% service level.
- `linear-programming/` — R examples using linear programming for a production mix and a transportation problem.

## Requirements

- Python 3 with Jupyter and the packages `numpy`, `pandas`, `matplotlib`, and `statsmodels` for the notebook.
- R with `forecast` and `tseries` for the time-series forecasting examples, `scatterplot3d` for the regression plots, and `lpSolve` for the optimization examples.
- The AirPassengers decomposition example uses R's built-in `datasets` package.

Each file is a standalone educational example. Open the notebook in Jupyter or run an R script in an R session after installing the packages used by that script.
