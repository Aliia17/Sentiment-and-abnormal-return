# Sentiment-and-abnormal-return

# News Events & Abnormal Stock Returns

This project explores the relationship between firm-specific news events and **abnormal stock returns**, using data from a Kaggle dataset. The analysis focuses on four major publicly listed companies — **Microsoft (MSFT), Nvidia (NVDA), Amazon (AMZN), and JPMorgan Chase (JPM)** — and investigates how different types of news affect stock price behavior.

---

## Objective

To test whether **firm-specific news events** lead to statistically significant **abnormal or cumulative abnormal returns (CARs)**, and whether certain types of events (e.g., operational vs. strategic) have different impacts on investor response.

---

## Methodology

- **Event Study Framework**: Estimated market model using an estimation window; calculated abnormal and cumulative abnormal returns in event windows.
- **Regression Analysis**: Tested the effect of news volume on abnormal return magnitude.
- **Hypothesis Testing**: Used t-tests to determine statistical significance of CARs.
- **Data Visualization**: Histograms, CAR plots, and return distributions analyzed across companies and event types.

---

## Key Findings

- News volume significantly influences the **magnitude** of abnormal returns (p = 0.0201).
- **Strategic and sentiment-related events** triggered stronger market reactions than routine announcements.
- Abnormal returns were statistically significant for most firms — especially AMZN and MSFT.
- **NVDA's personnel changes** caused a pronounced stock reaction, while dividend announcements showed limited effect.
- Return distributions deviated from normality, but large sample size justified the regression approach.

---

## Tools & Techniques

- **Python**, **Pandas**, **Matplotlib**, **Statsmodels**
- Data source: Kaggle [firm-specific news dataset]
- Financial metrics: Abnormal Returns, Cumulative Abnormal Returns (CAR), Skewness, Kurtosis, Volatility

---

## Conclusion

This project demonstrates that **not all news is equal** — investors react differently depending on the **type and volume** of firm-specific events. The results offer practical insights for analysts, investors, and financial strategists interested in market sentiment and event-driven trading.

---

## File Summary

- `news_event_stock_analysis.ipynb`: Complete code for preprocessing, analysis, and visualization
- `data/`: Contains preprocessed data samples (if not too large for GitHub)

---

## 💬 Contact

Feel free to reach out or open an issue if you'd like to discuss methodology or collaborate.

