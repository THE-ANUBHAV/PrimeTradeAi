# 📊 Market Sentiment vs Trader Behavior (Hyperliquid)

## 🎯 Objective
Analyze how Bitcoin market sentiment (Fear/Greed) impacts trader behavior and performance on Hyperliquid, and build a predictive model for profitability.

---

## 📁 Datasets
1. Fear & Greed Index (Bitcoin sentiment)
2. Hyperliquid Historical Trader Data

---

## ⚙️ Methodology

### Data Preparation
- Cleaned timestamps and aligned datasets by date
- Aggregated trading data to daily level
- Created metrics:
  - Daily PnL
  - Number of trades
  - Average trade size

---

## 📊 Key Insights

### 1. Fear Drives Profitability
- Highest PnL observed during **Extreme Fear**
- Traders capitalize on volatility

### 2. Greed Reduces Performance
- Lowest PnL during **Greed phases**
- Indicates overconfidence and poor entries

### 3. Behavior Shift
- Trade frequency increases in Fear
- Drops significantly in Greed

---

## 🧠 Strategy Recommendations

### Strategy 1: Fear Mode
- Increase trading activity
- Exploit volatility
- Slightly increase position size

### Strategy 2: Greed Mode
- Reduce trading
- Lower leverage
- Avoid overtrading

---

## 🤖 ML Model (Bonus)

### Goal
Predict next-day profitability (profit/loss)

### Features Used
- Sentiment classification
- Number of trades
- Average trade size
- Current day PnL

### Model
- Random Forest Classifier

### Output
- Binary prediction:
  - 1 = Profitable day
  - 0 = Loss day

---

## 🛠️ How to Run

```bash
pip install pandas scikit-learn matplotlib
