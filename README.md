# 📊 Financial Market Analysis & DCF Valuation (2019–2024)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Overview
This project performs an end-to-end financial analysis using a real-world historical dataset spanning **2019 to 2024**. The analysis covers multiple asset classes, including **Commodities, Equities, Crypto assets, and Global Indices**, to understand cross-asset correlations and risk-return profiles.

Additionally, the project includes a fundamental **Discounted Cash Flow (DCF)** valuation model for **Apple Inc. (AAPL)**, demonstrating the application of financial modeling techniques used in investment research and equity analysis.

---

## 🚀 Key Features

### 1. Data Cleaning & Preprocessing
* **Data Ingestion:** Loaded raw historical market data.
* **Sanitization:** Removed unwanted columns and handled missing values (`NaN`).
* **Formatting:** Converted date strings to datetime objects and standardized numeric fields.
* **Output:** Generated a clean, structured dataset ready for quantitative analysis.

### 2. Market Price Trend Analysis
Visualized historical price movements to identify long-term trends and market cycles for major assets:
* **Tech Giants:** Apple, Tesla, Microsoft, Amazon, Meta, Netflix.
* **Crypto:** Bitcoin, Ethereum.
* **Commodities:** Gold, Silver, Crude Oil, Natural Gas, Copper.
* **Indices:** S&P 500, Nasdaq 100.

### 3. Quantitative Risk & Return Analysis
* **Daily Returns:** Computed daily percentage changes to analyze volatility clusters.
* **Correlation Heatmap:** Generated a matrix to study diversification opportunities.
    * *Insight:* Crypto assets (BTC/ETH) are highly correlated.
    * *Insight:* Commodities show low correlation with Tech stocks (effective for hedging).
* **Volatility & Sharpe Ratio:** Calculated annualized volatility and risk-adjusted returns.

### 4. DCF Valuation Model (AAPL)
Built an intrinsic valuation model based on Free Cash Flow to Firm (FCFF).
* **Forecast Period:** 5 Years.
* **Assumptions:** WACC (8.5%), Terminal Growth Rate (2%).

---

## 📉 Key Findings & Insights

### Risk-Adjusted Performance (Sharpe Ratio)
Based on the analysis from 2019–2024, the assets were ranked by risk-adjusted returns:

| Rank | Asset | Performance Note |
| :--- | :--- | :--- |
| 🥇 | **Ethereum** | Top Performer |
| 🥈 | **Nvidia** | High Alpha Generation |
| 🥉 | **Bitcoin** | Strong Long-term Growth |
| 4 | **Tesla** | High Volatility / High Reward |
| 5 | **Apple** | Consistent Compounder |
| 🔻 | **Crude Oil** | Worst Performer (Negative Annual Return) |

### Valuation Conclusion: Apple (AAPL)
* **Enterprise Value:** $1.73 Trillion
* **Equity Value:** $1.40 Trillion
* **Intrinsic Value per Share:** **$94.76**
* **Market Price (Reference):** ~$170 - $190 range (2024)
* **Verdict:** Based on these conservative assumptions, **Apple appears overvalued** relative to its 2024 market price.

---

## 🛠️ Technologies Used
* **Python:** Core programming language.
* **Pandas & NumPy:** Data manipulation and vector calculations.
* **Matplotlib & Seaborn:** Financial visualization and heatmaps.
* **SciPy:** Statistical computations.

---

## 📂 Project Structure
```text
├── data/
│   ├── Stock Market Dataset.csv       # Original dataset
│   └── Cleaned_Stock_Market_Dataset.csv   # Preprocessed data used for analysis
├── notebooks/
│   ├── DCF.ipynb    # Preprocessing steps: Data Cleaning and Analysis
├── images/
│   ├── correlation_heatmap.png   # Correlation visualization
│   └── price_trends.png          # Asset performance charts
│   └── rolling_volatility.png    # (30-day) for selected assets
├── plot/
│   ├── 19 png   # 19 image in the plot folder charts with different relations
├── analysis_summary              # Short Analysis
├── README.md                     # Project documentation
└── risk_return_summary.excel     # Risk Return summary in Excel
```

## 📬 Contact Information

Thank you for reviewing this project! I am actively seeking opportunities and would love to connect.

| Channel | Details |
| :--- | :--- |
| **Name** | Jitesh Jangam |
| **Email** | `jangamjitesh1@gmail.com` |
| **LinkedIn** | linkedin.com/in/jitesh-jangam |

