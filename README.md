# Summary
Analyzing stock and revenue data for **Tesla** and **GameStop** using Python with "yfinance", "pandas", and "plotly".
## Project Overview
Installed and imported necessary libraries to work with stock data and build visualizations.  
Used **yfinance** to download historical stock prices and reset index for easier manipulation.  
Applied **web scraping** to extract revenue tables from websites, cleaned values (removed `$` and `,`), and converted them to numeric.  

Visualized closing stock prices and revenue trends using **Plotly** for interactive charts by defining "make_graph()" to plot both stock prices and revenue in a unified, reusable way.  
### Tools Used
- **Python**: for data extraction, cleaning, and visualization.  
- **JupyterLab**: interactive environment to write, run, and document code.  
- **pandas**: data manipulation, web-scraped table extraction, and cleaning (dates, revenues, filtering).  
- **yfinance**: extracting historical stock market data directly from Yahoo Finance.  
- **plotly.graph_objects**: creating detailed and interactive plots for stock price and revenue.  
- **plotly.subplots**: building dashboards (stock price vs revenue) with shared axes.  
- **plotly.io**: controlling rendering/display of plots within Jupyter environment.  
### Data Source
- **IBM / Coursera Data Science Project**
### Analysis
- Tesla Graph
<img width="1336" height="635" alt="Tesla_stock_gragh" src="https://github.com/user-attachments/assets/498fba5a-a58a-4dd0-a099-5294e1c587e5" />
- GameStop Graph
<img width="1340" height="635" alt="GameStop_graph" src="https://github.com/user-attachments/assets/cd309d84-6cc1-42c4-ba74-04e65f6271a6" />
