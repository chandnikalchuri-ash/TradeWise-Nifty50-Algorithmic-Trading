# TradeWise: Stock Performance Analysis & Backtesting

## 📌 Project Overview
"TradeWise" is a comprehensive data analytics and algorithmic trading project focused on the Indian Equity Market. The core objective of this project is to analyze 5 years of historical stock price data for the Top 20 Nifty 50 stocks, implement a systematic Moving Average (MA) Crossover strategy, and provide data-backed investment recommendations based on rigorous performance evaluation.

## 🎯 Primary Objectives
- **Data Preprocessing:** Clean and structure 5 years of daily market data (handling missing values, formatting chronologically).
- **Strategy Implementation:** Design and backtest a trend-following system using 20-Day (Short-term) and 50-Day (Long-term) Simple Moving Averages (SMA).
- **Performance Evaluation:** Quantify strategy success by calculating critical risk-reward metrics: Total Returns, Annualized Returns, Maximum Drawdown, and the Sharpe Ratio.
- **Strategic Recommendations:** Synthesize findings to identify the most robust stocks for a balanced investment portfolio.

## 🛠️ Tools & Technologies
- **Language:** Python
- **Libraries:** Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn (Data Visualization)
- **Environment:** Jupyter Notebook
- **Reporting:** MS Word (Business Insights), MS PowerPoint (Executive Presentation)

## 📊 Key Insights
- **Holistic Evaluation is Crucial:** Relying on a single metric is flawed. For example, while `ADANI_ENTERPRISES` yielded the highest total return (exponential growth), it carried significant volatility. Conversely, `NESTLE` offered exceptional stability (lowest maximum drawdown) but lacked exponential growth.
- **Risk vs. Reward Efficiency:** A strong positive correlation exists between the Sharpe Ratio and Total Return. Stocks positioned in the top-right quadrant of our analysis (e.g., `BAJAJ_FINANCE`, `ADANI_ENTERPRISES`) offered the most efficient risk-adjusted returns.
- **The Hedging Anomaly:** A correlation heatmap revealed widespread positive correlation among most Nifty 50 stocks, with `COAL INDIA` emerging as a unique anomaly exhibiting strong negative correlation—making it a prime candidate for portfolio hedging.
- **Strategy Vulnerability:** The 20/50 SMA crossover is profitable for trending stocks but struggles in choppy markets. The inherent lag of the 50-day MA fails to protect capital effectively during sudden market crashes.

## 💡 Strategic Recommendations
1. **Enhance Risk Management:** The basic moving average crossover is insufficient for strict risk control. Integrating a trailing stop-loss mechanism is highly recommended to exit trades earlier during market shocks and preserve capital.
2. **Construct a Blended Portfolio:**
   - *Aggressive Growth:* Allocate capital to `ADANI_ENTERPRISES` and `BAJAJ_FINANCE` for compounding wealth.
   - *Capital Preservation:* Include defensive stocks like `NESTLE` to cushion against deep drawdowns.
   - *Strategic Hedging:* Utilize inversely correlated assets like `COAL INDIA` to stabilize overall portfolio volatility.

## 📁 Repository Structure
- `Stock_Analysis.ipynb`: Contains the complete Python code for data cleaning, metric calculations, strategy implementation, and visualizations.
- `Stock Performance Analysis.pdf`: The detailed business report outlining all objective and subjective findings.
- `Stock Performance Analysis_Presentation.pdf`: The executive slide deck summarizing the project's methodology, key insights, and final recommendations.

---
*This project was completed by Chandni Kalchuri as part of a Data Analysis portfolio.*
