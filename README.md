# primetrade-sentiment-analysis
# Hyperliquid Performance Tracking vs. Bitcoin Market Sentiment

Production-grade data pipeline analyzing the correlation between granular Web3 trader execution strategies (Hyperliquid) and psychological macro regimes (Bitcoin Fear & Greed Index).

## 🚀 Key Uncovered Analytical Insights
Based on processing over 213,000 unique trade execution datapoints:
* **The "Greed" Sweet Spot:** Traders experienced their highest average profitability ($87.89 PnL per trade) during standard **Greed** phases, indicating strong trend-following execution validity.
* **The "Extreme Greed" Trap:** While **Extreme Greed** environments saw the highest average trade sizes ($5,660.26 USD), the win rate dropped severely relative to standard Greed phases, indicating over-leveraged account liquidation traps at market blow-off tops.
* **Fear Resiliency:** Traders managed an impressive **41.5% win rate** during market **Fear** regimes, capturing safe, strategic delta positions.

## 🛠️ Software Engineering & Architecture Hygiene
To align with production expectations:
1. **Timestamp Normalization:** Engine automatically handles multi-type variations by scaling Unix epoch millisecond floats (`float64`) down into uniform standard calendar strings (`YYYY-MM-DD`).
2. **Strict JSON Engine:** Compiles dynamic multi-group pandas metrics arrays directly into production-ready schemas inside `insights.json`.

## 📦 How to Run the Pipeline
1. Open `assignment_pipeline.ipynb` inside Google Colab.
2. Ensure your workspace directories point to your source data files.
3. Run all cells to auto-generate diagnostic charts and the strict JSON output payload.
