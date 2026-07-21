# InLook
An explainable, multi-factor stock recommendation engine that analyzes financial metrics and generates transparent Buy, Hold, or Sell ratings using Python.

The InLook Stock Analyzer uses publicly available financial data, scores companies across several key investment categories, and generates a transparent Buy, Hold, or Sell recommendation. Rather than acting as a "black box," every recommendation includes a breakdown of the factors that influenced the final score.

> **Disclaimer:** This project is intended for educational and portfolio purposes only and should not be considered financial advice.

---

## Features

- Financial statement analysis
- Valuation metrics
- Profitability metrics
- Growth metrics
- Financial health analysis
- Momentum analysis
- Weighted scoring system
- Transparent Buy/Hold/Sell recommendations
- Visual score breakdowns

---

## How It Works

The model evaluates a company across multiple investment categories.

### Valuation
- Price-to-Earnings (P/E)
- PEG Ratio
- Price-to-Book (P/B)
- Enterprise Value metrics

### Profitability
- Return on Equity (ROE)
- Return on Assets (ROA)
- Operating Margin
- Gross Margin

### Growth
- Revenue Growth
- Earnings Growth
- Free Cash Flow Growth

### Financial Health
- Current Ratio
- Debt-to-Equity
- Cash Position

### Momentum
- Price performance
- Moving averages
- Other trend indicators

Each metric contributes to a weighted score, producing a final rating out of 100.

---

## Example Output

```
Ticker: AAPL

Overall Score: 84/100

Category Scores
------------------------
Valuation          18/20
Profitability      19/20
Growth             17/20
Financial Health   15/20
Momentum           15/20

Recommendation:
🟢 BUY
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Yahoo Finance API (yfinance)

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/InLook.git
```

Install the required packages

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

or

```bash
python main.py
```

---

## Why I Built This

I built InLook to combine my interests in finance and data science. The goal was to create a recommendation system that is both quantitative and explainable, allowing users to understand why a stock receives its rating instead of relying on a black-box model.

This project demonstrates skills in:

- Data collection
- Financial analysis
- Python programming
- Data visualization
- Algorithm design
- Quantitative modeling
