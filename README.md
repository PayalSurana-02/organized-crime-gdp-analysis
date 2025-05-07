## Organized Crime & GDP Analysis

This project was developed as part of CIS 9650 – Programming for Analytics course at Baruch College.

This project explores how economic strength (GDP per capita) relates to organized crime activity across 193 countries. We combined global crime and economic datasets, cleaned and merged them using Python, and visualized trends through Seaborn and Plotly. The goal was to identify patterns in criminal markets, resilience scores, and their economic impacts.

### Files Included

- `crime_gdp_analysis.ipynb`: Python notebook with full analysis and visualizations
- `organized_crime.xlsx`: Raw crime dataset
- `gdp_per_capita.xlsx`: GDP per capita dataset
- `Executive Summary.pdf`: Brief overview of findings
- `Project PPT.pdf`: Full team presentation and insights

### Tools Used

- Python (pandas, seaborn, plotly, statsmodels)
- Excel
- Jupyter Notebook

### What we Did

- Cleaned and merged two Excel datasets (crime + GDP)
- Used pandas to align country names and prepare data
- Visualized indicators like heroin trade, human trafficking, and resilience using Seaborn, Plotly, and FacetGrid
- Ran linear regression using statsmodels to evaluate GDP impact factors
- Documented findings in an executive summary and presentation

### Key Insights

- Countries with high GDP per capita generally show stronger resilience to organized crime, but correlation is weak overall
- Heroin trade and human trafficking show strong regional patterns — highest in South Asia and parts of Africa
- Linear regression showed Resilience has the most statistically significant impact on GDP per capita
- Europe shows a clearer inverse relation between GDP and criminality compared to Africa or Asia
- The model explained ~36% of the GDP variance, suggesting other socio-political factors may be at play


### Project Report

📥 [Download Executive Summary](Executive%20Summary.pdf)  
📊 [View Project Presentation](Project%20PPT.pdf)
📎 [View Notebook](crime_gdp_analysis.ipynb)

