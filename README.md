# 🧠💰 Does Your Wallet Make You Depressed?
### Correlating Polish Financial Data with Depression Rates (2004–2024)

> *"Correlation does not imply causation — but it sure makes you think."*

---

## 🎯 Project Overview

This project explores a simple but provocative question: **Is there a statistical relationship between financial indicators and depression rates in Poland?**

We combine publicly available mental health data with financial and economic datasets to visualize potential correlations — not to prove causation, but to spark curiosity, discussion, and maybe a little existential dread.

This is a data engineering and data science project built for fun, transparency, and public insight.

---

## 📊 Datasets & Correlations Explored

| Financial Indicator | Data Source | Period |
|---|---|---|
| NBP Interest Rates | National Bank of Poland | 2004–present |
| Bitcoin Price (BTC/PLN) | Yahoo Finance | 2013–present |
| Warsaw Apartment Prices | GUS / NBP | 2006–present |
| Inflation (CPI) | GUS | 2004–present |
| WIG20 Stock Index | Yahoo Finance | 2004–present |

**Depression data source:** WHO / Eurostat / GUS (National Health Surveys)


---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.14 | Core language |
| Pandas | Data manipulation |
| DuckDB | Local SQL database |
| Plotly | Interactive charts |
| Streamlit | Web dashboard |
| SciPy | Statistical correlation |
| yfinance | Financial data API |

---

## 🏗️ Project Structure
```
depression-finance-pl/
├── data/
│   ├── raw/          # Raw data from APIs and CSV files
│   ├── processed/    # Cleaned and normalized data
│   └── final/        # Analysis-ready datasets
├── pipeline/
│   ├── extract.py    # Data extraction from APIs
│   ├── transform.py  # Cleaning and normalization
│   └── load.py       # Loading into DuckDB
├── analysis/
│   └── correlations.py  # Statistical analysis
├── viz/
│   └── dashboard.py     # Streamlit dashboard
└── requirements.txt
```

---

## 🚀 Getting Started
```bash
git clone https://github.com/YOUR_USERNAME/depression-finance-pl.git
cd depression-finance-pl
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run viz/dashboard.py
```

---

## 📈 Results & Dashboard

*Coming soon — dashboard screenshots and correlation findings will be added here.*

---

## ⚠️ Disclaimer

This project is for educational and entertainment purposes only. Correlation does not imply causation. If you are struggling with depression, please reach out to a mental health professional.

**Poland crisis helpline: 116 123**

---

## 👨‍💻 Author

**Maciej Reluga** — built with curiosity, Python, and too much coffee.

*Feel free to fork, contribute, or just star the repo if it made you smile!* ⭐