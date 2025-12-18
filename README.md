# UK-House-Prices (2000–2025)

![Python](https://img.shields.io/badge/python-3-blue)
![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue)
![Project Status](https://img.shields.io/badge/status-completed-brightgreen)




Analysis of **UK house price trends across regions** and the **relationship with Bank of England interest rates**. Demonstrates **data analysis, visualization, and economic insight** using Python.

---

## Project Structure
```
Data/
   UK-House-Prices.csv
   Bank Rate history and data Bank of England Database.xlsx
house_price_analysis.py
plots/
README.md
```

- **Data:** Raw house price and interest rate datasets.  
- **Python script:** Processes data, generates metrics, and saves plots in `plots/`.  

---

## Visualizations

### House Prices by Region
![House Prices by Region](Plots/house_prices_by_region.png)

### Annual House Price Growth
![House Price Growth](Plots/house_price_growth_by_region.png)

### Rolling 12-Month Growth
![Rolling 12-Month Growth](Plots/rolling_12m_house_price_growth.png)

### House Price Growth vs Bank Rate
![Growth vs Bank Rate](Plots/house_price_growth_vs_base_rate.png)

### Scatter Plot: Rate vs Growth
![Scatter Rate vs Growth](Plots/scatter_rate_vs_growth.png)

---

## Key Findings
- Significant **regional disparities** in house price growth.  
- **Interest rates influence house price growth**, with lagged rates showing predictive patterns.  
- Insights highlight **UK housing market dynamics** over the last two decades.  

---

## Skills Demonstrated
- **Data cleaning & preprocessing:** resampling, pivoting, handling missing values  
- **Data visualization:** line plots, dual-axis plots, scatter plots, rolling averages  
- **Economic analysis:** evaluating interest rate impacts on housing  
- **Python programming & reproducibility:** automated generation of professional plots  

---

## Usage
1. Clone the repo: 

```bash
git clone https://github.com/OliJDKirk/UK-House-Prices
```

2. Install libraries:

```bash
pip install pandas matplotlib numpy
```

3. Run analysis:  

```bash
python house_price_analysis.py
```

All visualizations are saved in `plots/`.
