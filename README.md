# Gross Profit Growth Decomposer

Splits Titan Company's year-over-year Gross Profit growth into
two drivers: Revenue Effect (growth from selling more) and
Margin Effect (growth from margin expansion/contraction).

**Tech:** Python, yfinance, pandas, matplotlib

**Method:** standard price/volume-style variance decomposition,
applied to gross margin instead of unit price.

**Run it:**
```
pip install yfinance pandas matplotlib
jupyter notebook revenue_growth_decomposer.ipynb
```

![chart](
