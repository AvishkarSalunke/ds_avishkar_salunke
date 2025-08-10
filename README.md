
##  Datasets
1. **Bitcoin Market Sentiment Dataset**  
   - Columns: `Date`, `Classification` (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)
2. **Historical Trader Data from Hyperliquid**  
   - Columns: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.

##  Methodology
1. Data loading and cleaning
2. Merging sentiment and trader datasets on date
3. Feature engineering (trade volume, avg PnL, position size)
4. Exploratory Data Analysis (EDA) and visualizations
5. Insights extraction and summarization

##  Key Insights
- **Total trades analyzed**: 211,218  
- **Most common sentiment**: Fear  
- **Highest avg PnL**: Extreme Greed  
- **Largest avg position size**: Extreme Greed  
- **Highest total trade volume**: Fear  

##  How to Run
1. Open the Google Colab link below.
2. Run all cells to reproduce the analysis.
3. Check the `outputs/` folder for generated visualizations.
4. Refer to `ds_report.pdf` for the final summary.

##  Google Colab Link
[Open Notebook in Google Colab](https://colab.research.google.com/drive/1yaJISw8PN7QpvyvmW4VRWPg7g7KNYFOE?usp=sharing)
