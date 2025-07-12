# 📈 Stock Market Analysis & Prediction (AAPL, GOOG, MSFT, AMZN)

This project performs **time series analysis** and **stock price prediction** for major tech companies — **Apple (AAPL), Google (GOOG), Microsoft (MSFT), and Amazon (AMZN)** — using historical market data from **Yahoo Finance**.

The analysis explores:
- 📊 Stock price trends
- 📉 Daily returns and moving averages
- 🔗 Correlation between companies
- 💹 Volume & volatility
- 🔮 Future price prediction using **LSTM (Long Short-Term Memory)** — a deep learning model suited for sequential/time series data

---

## 🚀 Key Features

- 📥 **Data Collection:** Using `yfinance` to fetch historical data
- 📊 **Visualization:** Trend charts, moving averages, volume plots with Matplotlib/Seaborn
- 📈 **Return & Risk Analysis:** Daily returns, correlation, and volatility
- 🧠 **LSTM Modeling:** Forecasting future stock prices (Apple Inc.)
- 🧪 **Evaluation:** Visual comparison of actual vs predicted prices

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- yfinance
- TensorFlow / Keras (for LSTM)

---

## 📂 Structure

├── stock_analysis_lstm.ipynb
├── README.md
├── plots/
│ └── (optional graphs and visualizations)



---

## 📌 How to Run

1. Clone the repository
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
Run the notebook:


jupyter notebook stock_analysis_lstm.ipynb
📚 Goals Answered
What was the change in stock price over time?

What was the average daily return?

What are the moving averages and correlations?

What’s the risk of investing in a stock?

Can we predict future stock prices using LSTM?

📍 Note
Data is pulled from Yahoo Finance and may vary depending on the current date/time you run the notebook.