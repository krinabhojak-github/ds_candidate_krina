

# Data Science Assignment: Web3 Trading Team
## Project Description
This project analyzes trader behavior in the Web3 trading ecosystem by correlating Bitcoin Market Sentiment data (Fear/Greed classifications) with Historical Trader Data (e.g., account, symbol, execution price, size, side, time, closedPnL, leverage). The objective is to identify trends in profitability, leverage, and trade volume across market sentiment periods and propose data-driven trading strategies. The analysis is conducted in a Google Colab notebook `(notebook_1.ipynb)`, with results summarized in `ds_report.pdf` and visualizations in the `outputs` folder.
## How to Install and Run the Project:
### Open the Notebook in Google Colab:
* Access the notebook via the provided link: Notebook 1.
* No local installation is required, as the notebook runs in Google Colab’s cloud environment.

### Dependencies:
* The notebook uses Python libraries (e.g., pandas, numpy, matplotlib, seaborn, scipy) pre-installed in Colab.
* Ensure a stable internet connection to run the notebook.

### Run the Notebook:
* Open the Colab link.
* `Click Runtime` > `Run all` to execute all cells.
* The notebook automatically loads datasets from `csv_files` and generates visualizations in `outputs`.


## How to Use the Project

### Explore the Notebook:
Review `notebook_1.ipynb` in Colab to see data cleaning, merging, exploratory data analysis (EDA), and statistical tests (e.g., t-tests comparing profitability in Fear vs. Greed periods).


## View Results:
Check `ds_report.pdf` for a detailed summary of findings and proposed trading strategies.
Inspect visualizations in `outputs`:
`sentiment_trend.png`: Market sentiment over time.
`profit_by_sentiment.png`: Profitability by sentiment.
`leverage_by_sentiment.png`: Leverage usage by sentiment.
`volume_by_sentiment.png`>: Trade volume by sentiment.


## Datasets:
`csv_files/cleaned_sentiment.csv`: Processed Bitcoin Market Sentiment data (`Date`, `Classification`).
`csv_files/cleaned_trader_data.csv`: Processed Historical Trader Data (`account`, `symbol`, etc.).

## Reproduce Analysis:
Upload `cleaned_sentiment.csv` and `cleaned_trader_data.csv` to Colab if prompted.
Follow the notebook’s instructions to rerun the analysis.

## Credits

Candidate: krina
Datasets: Provided by the Web3 Trading Team as part of the assignment.
Tools: Google Colab, Python (pandas, numpy, matplotlib, seaborn, scipy).
Guidance: Instructions and requirements from the Web3 Trading Team. 
