
---

# Task 2 — README.md

```md
# Stock Price Prediction Using Machine Learning

## Objective
The objective of this project is to predict the next day's stock closing price using historical stock market data and machine learning techniques.

---

## Dataset
Historical stock data was fetched using the `yfinance` Python library.

Example stocks:
- Apple (AAPL)
- Tesla (TSLA)

Features used:
- Open
- High
- Low
- Volume

Target:
- Close Price

---

## Technologies Used
- Python
- Pandas
- NumPy
- yfinance
- scikit-learn
- Matplotlib

---

## Project Workflow

### 1. Data Collection
Used the `yfinance` API to download historical stock data.

Example:
```python
import yfinance as yf

data = yf.download("AAPL", start="2020-01-01", end="2025-01-01")