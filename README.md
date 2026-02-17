# Egypt Purchasing Power Analysis (2010–2024)

## Project Objective
To evaluate whether purchasing power in Egypt improved or declined between 2010 and 2024 using real macroeconomic indicators.

---

## Research Question
Did income growth outpace inflation over the long term?

---

## Data Sources
- World Bank – Inflation (CPI, annual %)
- World Bank – Real GDP per capita (constant prices)

---

## Methodology

1. Filtered Egypt data (2010–2024)
2. Converted data to long format for time-series analysis
3. Used Real GDP per capita to avoid double-adjusting for inflation
4. Created an index (2010 = 100) to measure cumulative change
5. Visualized long-term trend

---

## Key Findings

- Real GDP per capita index increased from **100 (2010)** to **~127 (2024)**
- This represents a **+27% cumulative increase**
- Despite economic shocks (2017, 2023), long-term purchasing power appears structurally resilient

---

## Visualization

![GDP Trend](gdp_trend.png)

---

## Tools & Technologies
- Python
- Pandas
- Seaborn / Matplotlib
- Jupyter Notebook

---

## Interpretation Notes

This analysis focuses on long-term structural change rather than short-term economic volatility.
While specific years show significant shocks, cumulative real income growth suggests overall purchasing power expansion over the studied period.
Jupyter Notebook
