# 📈 AlphaPulse — Investment Risk & Volatility Monitor

> A quantitative finance analytics project for portfolio risk monitoring using Monte Carlo simulation, Value at Risk (VaR), rolling volatility analysis, and stock correlation heatmaps.

---

## 🖼️ Overview

**AlphaPulse** is a financial analytics and risk modeling system built in Python to analyze portfolio behavior under market uncertainty.
The project simulates thousands of possible market scenarios, measures portfolio risk exposure, and visualizes asset relationships through interactive financial dashboards.

The system focuses on:

* portfolio diversification analysis
* probabilistic risk forecasting
* volatility monitoring
* statistical validation of market behavior

---

## ⚙️ Tech Stack

| Category             | Tools              |
| -------------------- | ------------------ |
| Programming          | Python             |
| Financial Data       | yfinance           |
| Data Analysis        | Pandas, NumPy      |
| Statistical Modeling | SciPy              |
| Visualization        | Plotly, Matplotlib |
| Dashboarding         | Dash               |
| Version Control      | Git & GitHub       |

---

## 📂 Project Structure

```text
AlphaPulse/
│
├── Data_Collection_and_Risk_Analysis.ipynb
├── 02_Monte_Carlo_Visualization.ipynb
│
├── outputs/
│   ├── prices.csv
│   ├── returns.csv
│   ├── monte_carlo_results.csv
│   └── plot1_monte_carlo_paths.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 Features

### 📥 Financial Data Collection

* Retrieved historical market data using `yfinance`
* Collected 5 years of adjusted closing prices
* Included 10 diversified assets across sectors:

  * Technology
  * Finance
  * Healthcare
  * Energy
  * Consumer
  * Automotive
  * Pharma
  * S&P 500 Index

---

### 📐 Quantitative Portfolio Analytics

#### Daily Log Returns

Calculated logarithmic returns for accurate financial modeling and simulation.

Formula:

```text
r(t) = ln(Pt / Pt-1)
```

---

### 🎲 Monte Carlo Simulation

* Simulated **10,000 portfolio paths**
* Forecasted 1-year portfolio performance
* Generated probabilistic future portfolio distributions
* Estimated downside market risk

---

### 📉 Value at Risk (VaR)

Calculated portfolio Value at Risk at 95% confidence level.

```text
VaR (95%) → Estimated worst expected portfolio loss under normal market conditions
```

---

### 📊 Correlation Heatmaps

* Measured inter-stock relationships
* Analyzed diversification opportunities
* Identified positively and negatively correlated assets

---

### 📈 Rolling Volatility Analysis

* Computed rolling 30-day volatility
* Monitored changing market uncertainty over time
* Compared portfolio stability across periods

---

### 📑 Statistical Validation

Performed statistical diagnostics on simulated and historical returns:

| Metric            | Purpose                                   |
| ----------------- | ----------------------------------------- |
| Skewness          | Measures asymmetry in return distribution |
| Kurtosis          | Measures tail-risk and extreme events     |
| Shapiro-Wilk Test | Tests normality assumption                |
| Q-Q Plot          | Visual normality validation               |

---

## 📊 Visualizations

The project includes:

* Monte Carlo simulation paths
* Final portfolio value distribution
* VaR distribution analysis
* Correlation heatmaps
* Rolling volatility charts
* Statistical validation plots

---

## 📦 Installation

```bash
git clone https://github.com/anubrata2209/alphapulse-risk-monitor.git

cd alphapulse-risk-monitor

pip install -r requirements.txt
```

---

## ▶️ Run Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open and run:

```text
Data_Collection_and_Risk_Analysis.ipynb
```

---

## 📋 Requirements

```txt
yfinance
numpy
pandas
scipy
plotly
matplotlib
dash
```

Install manually:

```bash
pip install yfinance numpy pandas scipy plotly matplotlib dash
```

---

## 📚 Financial Concepts Used

| Concept                | Description                                              |
| ---------------------- | -------------------------------------------------------- |
| Log Returns            | Stable mathematical representation of percentage returns |
| Monte Carlo Simulation | Probabilistic future market simulation                   |
| Value at Risk (VaR)    | Downside portfolio risk estimation                       |
| Correlation            | Relationship between asset movements                     |
| Volatility             | Measurement of market uncertainty                        |
| Skewness               | Direction of distribution asymmetry                      |
| Kurtosis               | Probability of extreme events                            |

---

## 💼 Business Use Case

AlphaPulse can support:

* portfolio risk assessment
* investment strategy analysis
* diversification planning
* financial analytics reporting
* market uncertainty modeling

---
