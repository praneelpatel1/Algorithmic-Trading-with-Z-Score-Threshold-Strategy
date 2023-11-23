# Algorithmic-Trading-with-Z-Score-Threshold-Strategy

This project is a trading algorithm designed for QuantConnect's Lean Algorithm Framework. It utilizes the concepts of pairs trading and incorporates various statistical concepts such as the Augmented Dickey-Fuller test, half-life calculation, and Hurst exponent.

### Key Features:

- **_Pairs Trading Strategy:_** Utilizes statistical arbitrage through mean reversion in pairs trading. The algorithm dynamically selects pairs of stocks and trades them based on their relative performance.

- **_Statistical Tests for Mean Reversion:_** Employs the Augmented Dickey-Fuller test to identify mean-reverting spreads between pairs of stocks.

- **_Hurst Exponent and Half-Life Calculations:_** Determines the degree of mean reversion and the time period for half of the mean reversion to occur.

- **_Incorporation of SEC Reports:_** Enhances trading decisions by analyzing SEC reports like 8-K, 10-K, and 10-Q for relevant stocks.

- **_Dynamic Universe Selection:_** The algorithm selects stocks based on real-world criteria, focusing on major companies for stable and significant trading opportunities.

### **How to Use:**

**_Setting Up:_** Install QuantConnect's Lean Algorithm Framework. Clone this repository and ensure all dependencies, like statsmodels and numpy, are installed.

**_Customization:_** Adjust the parameters like lookback_period, entry_z_score_threshold, and exit_z_score_threshold to fit your trading style.
Running the Algorithm: Deploy the algorithm on QuantConnect's platform or locally using Lean. Monitor the performance and adjust the universe of stocks as needed.

### **Resources**:

1. QuantConnect's Lean Documentation: [Lean Algorithm Framework](https://www.quantconnect.com/docs/algorithm-framework/overview)
2. SEC Report Analysis: [SEC Filings & Forms](https://www.sec.gov/edgar.shtml)
3. statsmodels Documentation: [Statsmodels](https://www.statsmodels.org/stable/index.html)
4. Understanding Pairs Trading: [Investopedia - Pairs Trading](https://www.investopedia.com/terms/p/pairstrade.asp) 

This project aims to provide a sophisticated yet accessible approach to algorithmic trading, leveraging both quantitative analysis and financial report insights. It is a simple yet incredibly captivating introduction for exploring advanced trading strategies. I plan on building this project to use more advanced statistical methods. Additionally, I hope to incorporate GenerativeAI into the project. I believe this could be particularly beneficial for the stock selection aspect of the project. Advanced AI models would be able to parse through financials, as well as news reports and trends, allowing the algorithm to perform a more holistic assessment of companies.
