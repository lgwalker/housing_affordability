# Housing Affordability Crisis Analysis

A DATA303 final project analyzing housing price-to-income ratios across U.S. metro areas from 1980-2024.

https://lgwalker.github.io/housing_affordability/ 

## Research Questions

1. **The Great Decoupling**: How has the national average price-to-income ratio shifted from the historical norm (1980-2000) compared to the post-2020 era?

2. **The Affordability Ceiling**: In 2024, how many metros have surpassed a ratio of 5.0 (the threshold for "severely unaffordable")?

3. **Geographic Volatility**: Which U.S. metro areas experienced the greatest long-term volatility in housing affordability?

## Files

| File | Description |
|------|-------------|
| `homePriceIncomeRatio.ipynb` | Jupyter notebook with data analysis |
| `index.html` | Website homepage |
| `styles.css` | Website styles |
| `images/trend.png` | Price-to-income ratio over time chart |
| `images/bar.png` | Unaffordable metros comparison |
| `images/map_with_tooltips.html` | Interactive volatility map |

## Running the Website

Option 1 - Open directly:
```bash
open index.html
```

Option 2 - Use Python's HTTP server:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000`

## Data Source

Federal Housing Finance Agency (FHFA) & U.S. Census Bureau
