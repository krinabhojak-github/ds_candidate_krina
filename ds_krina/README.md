ds_JohnDoe/
├── notebook_1.ipynb
├── ds_report.pdf
├── README.md
├── csv_files/
│   └── cleaned_sentiment.csv
│   └── cleaned_trader_data.csv
├── outputs/
│   └── sentiment_trend.png
│   └── profit_by_sentiment.png
│   └── leverage_by_sentiment.png
│   └── volume_by_sentiment.png

# Data Science Assignment: Web3 Trading Team
## Project Description
This project analyzes trader behavior in the Web3 trading ecosystem by correlating Bitcoin Market Sentiment data (Fear/Greed classifications) with Historical Trader Data (e.g., account, symbol, execution price, size, side, time, closedPnL, leverage). The objective is to identify trends in profitability, leverage, and trade volume across market sentiment periods and propose data-driven trading strategies. The analysis is conducted in a Google Colab notebook <sub>(notebook_1.ipynb)</sub>, with results summarized in <sub>ds_report.pdf</sub> and visualizations in the <sub>outputs</sub> folder.
## How to Install and Run the Project:
### Open the Notebook in Google Colab:
* Access the notebook via the provided link: Notebook 1.
* No local installation is required, as the notebook runs in Google Colab’s cloud environment.

### Dependencies:
* The notebook uses Python libraries (e.g., pandas, numpy, matplotlib, seaborn, scipy) pre-installed in Colab.
* Ensure a stable internet connection to run the notebook.

### Run the Notebook:
* Open the Colab link.
* <sub>Click Runtime</sub> > <sub>Run all</sub> to execute all cells.
* The notebook automatically loads datasets from <sub>csv_files</sub> and generates visualizations in <sub>outputs</sub>.


## How to Use the Project

### Explore the Notebook:
Review <sub>notebook_1.ipynb</sub> in Colab to see data cleaning, merging, exploratory data analysis (EDA), and statistical tests (e.g., t-tests comparing profitability in Fear vs. Greed periods).


## View Results:
Check <sub>ds_report.pdf</sub> for a detailed summary of findings and proposed trading strategies.
Inspect visualizations in <sub>outputs</sub>:
<sub>sentiment_trend.png</sub>: Market sentiment over time.
<sub>profit_by_sentiment.png</sub>: Profitability by sentiment.
<sub>leverage_by_sentiment.png</sub>: Leverage usage by sentiment.
<sub>volume_by_sentiment.png</sub>: Trade volume by sentiment.


## Datasets:
<sub>csv_files/cleaned_sentiment.csv</sub>: Processed Bitcoin Market Sentiment data (<sub>Date</sub>, <sub>Classification</sub>).
<sub>csv_files/cleaned_trader_data.csv</sub>: Processed Historical Trader Data (<sub>account</sub>, <sub>symbol</sub>, etc.).

## Reproduce Analysis:
Upload <sub>cleaned_sentiment.csv</sub> and <sub>cleaned_trader_data.csv</sub> to Colab if prompted.
Follow the notebook’s instructions to rerun the analysis.

## Credits

Candidate: krina
Datasets: Provided by the Web3 Trading Team as part of the assignment.
Tools: Google Colab, Python (pandas, numpy, matplotlib, seaborn, scipy).
Guidance: Instructions and requirements from the Web3 Trading Team. 
