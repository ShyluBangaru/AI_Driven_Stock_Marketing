# AI_Driven_Stock_Marketing

# 📈 AI-Driven Stock Market Prediction and Trading Strategy Optimization

This project develops an intelligent trading system that integrates machine learning, deep learning, reinforcement learning, and financial theory to forecast market trends, detect anomalies, and optimize portfolio decisions. It is based on 1.5 years of stock data for 30 major U.S. tickers, collected from Yahoo Finance and SEC listings.

---

## 🎯 Objective

- Predict stock prices using deep learning models.
- Optimize asset allocation with risk-return balancing.
- Detect abnormal market activity suggestive of insider trading.
- Build a reinforcement learning-based decision system for Buy/Hold/Sell actions.

---

## 📊 Dataset Overview

- **Source:** Yahoo Finance, SEC Company Listings
- **Period:** Sep 2022 – Feb 2024
- **Features:** Ticker, Date, Open, High, Low, Close, Volume, plus engineered indicators (MACD, RSI, EMA, Returns, Volatility)
- **Stocks Covered:** 30 major tickers from diverse sectors

---

## 🧠 Techniques & Models Used

### 🔹 Model 1: Smart Portfolio Optimization
- Based on Modern Portfolio Theory (MPT)
- Simulated 10,000 portfolios
- Evaluated with **Sharpe Ratio**
- Output: Optimal portfolio with max return and minimal risk

### 🔹 Model 2: Anomaly Detection
- Used rolling Z-scores and volume spike thresholds
- Flagged irregular trading behavior
- Effective for **insider trading and manipulation detection**

### 🔹 Model 3: Next-Day Price Prediction
- Deep Learning with **LSTM**
- 60-day time window; MinMax scaling
- RMSE used for evaluation
- Achieved high accuracy across 20+ stocks

### 🔹 Model 4: Hidden Correlation Discovery
- Pearson Correlation + Hierarchical Clustering
- Helped group similar stocks for **diversification**
- Enabled sectoral behavior detection

---

## 📈 Performance Metrics

| Model         | Metric                  | Result Highlights                                  |
|---------------|--------------------------|----------------------------------------------------|
| LSTM          | RMSE                    | < $1.50 for most stocks, high accuracy on ABBV, AMZN |
| MPT Portfolio | Sharpe Ratio            | Identified NVDA, NVO, COST, META, SAP as optimal   |
| Anomaly       | Z-Score / Volume Spike  | Detected >3σ deviations and 3x volume surges       |
| Correlation   | Pearson + Dendrogram    | Clustered TSLA/META/NVDA together, XOM/LLY as diverse |

---

## 📊 Exploratory Data Analysis (EDA)

- Line plots for stock trends
- RSI to detect overbought/oversold signals
- Volume spike analysis for potential market activity
- Rolling volatility charts across sectors

---

## 🛠️ Tools & Libraries

- **Python**, **NumPy**, **pandas**, **scikit-learn**
- **TensorFlow/Keras** for LSTM
- **Matplotlib**, **Seaborn**
- **Yahoo Finance API**, **MinMaxScaler**
- **Deep Q-Learning** for RL modeling

---

## 🔮 Future Enhancements

- Integrate real-time sentiment data (e.g., news, tweets)
- Explore **Graph Neural Networks** for market relationships
- Use **Proximal Policy Optimization (PPO)** for advanced RL
- Add live-paper trading and backtesting environments
- Develop explainable AI justifications for decisions

---

## 📚 References

- [Stock Dataset from Yahoo Finance](https://finance.yahoo.com/)
- [Chen, Z. (2024). Portfolio Optimization Using ML](https://doi.org/10.62051/sdqv4p21)
- [Sen et al., (2021). LSTM in Portfolio Prediction](https://arxiv.org/abs/2111.04709)
- [Jiang et al., (2017). Deep RL for Portfolio Management](https://arxiv.org/abs/1706.10059)

*(Full references listed in report)*

---

## 👥 Contributors

- **Shylendra Sai Bangaru**
- Supervised by **Prof. Sumona Mondal**

---
