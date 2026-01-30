# Trader Behavior Insights: Market Sentiment Analysis

## 📌 Problem Statement
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index)
and trader performance using historical trading data from Hyperliquid. The objective is to
identify sentiment-driven behavioral patterns and extract insights that can inform smarter
trading strategies.

---

## 📊 Datasets Used

### 1. Bitcoin Fear & Greed Index
- Date
- Sentiment Classification (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)
- Sentiment Value (0–100)

### 2. Hyperliquid Historical Trader Data
- Account
- Coin
- Execution Price
- Trade Size (Tokens & USD)
- Side (BUY / SELL)
- Closed PnL
- Timestamp

---

## 🧠 Methodology

1. Cleaned and standardized timestamps across datasets
2. Merged trader data with daily market sentiment
3. Performed exploratory data analysis (EDA)
4. Evaluated trader performance across sentiment regimes
5. Analyzed trade direction, position sizing, and risk behavior
6. Visualized PnL distributions and trade frequency

---

## 📈 Key Insights

- **Higher average profitability during Greed and Extreme Greed periods**
- **Extreme Fear is associated with increased trading activity but lower returns**
- **Short (SELL) trades outperform during Fear-driven markets**
- **Buy-side trades dominate profitability during Greed phases**
- **Larger position sizes are observed during Greed, increasing exposure and drawdown risk**
- Emotional trading behavior intensifies during extreme sentiment conditions

---

## 📊 Visualizations Included
- PnL distribution by market sentiment
- Trade frequency by sentiment
- Buy vs Sell performance across sentiment regimes
- Average trade size vs sentiment

---

## 🧾 Conclusion & Strategy Implications

Market sentiment has a measurable impact on trader behavior and performance. 
Sentiment-aware trading strategies—such as favoring long positions during Greed
and defensive or short strategies during Fear—demonstrate improved outcomes.
Incorporating sentiment indicators can enhance risk management and decision-making
in crypto trading environments.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📬 Author
Utsav Sharma  
