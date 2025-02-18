# bitcoinDataAnalysis

This Jupyter Notebook analyzes historical Bitcoin price data (April 28, 2013 – July 31, 2017) to uncover trends, volatility patterns, and key statistical insights. The dataset includes daily metrics: High, Low, Volume, and Market Cap.

Key Visuals & Business Insights

**Price Trends Over Time**

Visual: Line charts for High and Low prices across the 4-year period.

Insights:
- Bitcoin exhibited significant volatility, with sharp price spikes and corrections.
- Long-term upward trend despite short-term fluctuations, reflecting growing market adoption.
- Correlation between High/Low ranges and major market events (e.g., regulatory news, adoption milestones).


**Volume vs. Price Movement**

Visual: Line plots comparing Volume and Close prices.

Insights:
- High trading volumes often coincided with price peaks, suggesting speculative activity.
- Low volume periods correlated with price stagnation, indicating reduced market participation.

**Market Cap Trends**

Visual: Line chart tracking Market Cap growth.

Insights:
- Exponential growth in market cap, aligning with Bitcoin’s price appreciation and increased investor interest.
- Market cap stability during consolidation phases highlights Bitcoin’s maturing asset class status.

**Statistical Summary**

Visual: Tabular summary of key metrics (mean, standard deviation, quartiles).

Insights:
- 25% of days had lows below $248.84, indicating frequent bearish corrections.
- 75th percentile close price at $663.40, underscoring rapid price recovery post-dips.

**Technical Best Practices**
  Data Cleaning: Handled missing values and converted dates to datetime objects.
  Visualization: Used Matplotlib/Seaborn for trend analysis and volatility mapping.
  Statistical Analysis: Generated descriptive statistics to quantify market behavior.
  Reproducibility: Structured code with clear comments and modular steps.
