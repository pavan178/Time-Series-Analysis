# Statistical Analysis and Time Series Visualization 📊
---

#### Description:
This repository contains Python scripts for statistical analysis and time series visualization. Two main scripts are provided, each addressing distinct statistical phenomena and data sets.

---

## Central Limit Theorem Demonstration

#### Overview:
This script demonstrates the Central Limit Theorem (CLT) using the t-distribution and analyzes sample means' convergence towards a normal distribution.

#### Requirements:
- `numpy`
- `matplotlib`
- `scipy`

#### Usage:
- Run the script `clt_demo.py` to visualize the CLT in action.
- Adjust parameters `k` and `N_values` for different t-distribution configurations.

#### Observations:
- The script compares sample means' distribution for different sample sizes (N) using histograms and QQ plots.
- Optimal sample size (N = 30) is suggested based on the closer alignment with the CLT and lighter tails.

---

## Time Series Analysis of Dow Jones Industrial Average

#### Overview:
This script analyzes the Dow Jones Industrial Average time series data, focusing on daily returns, rolling averages, and parameter estimation.

#### Requirements:
- `pandas_datareader`
- `numpy`
- `matplotlib`
- `scipy`

#### Usage:
- Run the script `dow_jones_analysis.py` to perform the analysis.
- Ensure proper dependencies are installed and accessible.

#### Key Highlights:
- Visualizes Dow Jones Industrial Average time series and computes daily returns.
- Analyzes sample averages and rolling averages of daily returns.
- Estimates distribution parameters using Maximum Likelihood Estimator (MLE) and `scipy`'s fit function.
- Provides insights into the behavior of daily returns and distribution characteristics.

---
