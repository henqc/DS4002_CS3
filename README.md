## Analysis of the impact that the Financial Crisis of 2008 had on Global Alcohol Consumption
### Allison Kerper, Elijah Kim, and Henry Chen
Hypothesis: We expect to see an increase of at least 20% in alcohol consumption following the financial crisis of 2008. 

Our data will be taken from The Global Health Observatory under the World Health Organization [1]. The data set will contain the year, location, gender, and type of alcohol consumed. The data is then analyzed using the ARIMA statistical model and Python package. 

## Software and Platform
- Types of software used:
    - Python Jupyter Notebook
        - Done in Google Colab
    - Python Packages Used:
        - NumPy
        - Pandas
        - Seaborn
        - datetime
        - matplotlib
        - ARIMA
        - SARIMAX
        - mean_squared_error
        - plot_acf
        - plot_pacf
        - adfuller
- Platform:
    - Ubuntu distribution on Linux (ran on Google Colab)

## Documentation Map
- DATA/
    - SA_0000001400.csv
- SCRIPTS/
    - Draft1.ipynb
- OUTPUT/
    - RESULTS.pdf
- README.md
- LISCENSE.md


## Instructions for Reproducing
- Download data from WHO [1]
- Unzip file to get SA_0000001400.csv
- Export those CSV files and upload to github
- In a Google Colab notebook, clean data keeping columns related to Time Dimension, SpatialDimensionCode1, and Alcohol Type
- Filter SpatialDimensionCodes keeping the US, UK, Germany, and Japan
- Use ARIMA statistical model in Python to find trends and predictions of the data based on those countries and further analyze whether alcohol types spiked in those countries at that time 
    - This can be done by using predict() function from installed packages [4][5]
- Analyze trends to see if there is a significance change over time 

## References:
[1] “Levels of Consumption,” www.who.int. https://www.who.int/data/gho/data/themes/topics/topic-details/GHO/levels-of-consumption

[2] Office of the United States Trade Representative, “Economy & Trade,” Office of the United States Trade Representative, 2018. Available: https://ustr.gov/issue-areas/economy-trade

[3] E. D. Nesoff, S. Gutkind, S. Sirota, A. L. McKowen, and C. B. Veldhuis, “Mental health and economic stressors associated with high-risk drinking and increased alcohol consumption early in the COVID-19 pandemic in the United States,” Preventive Medicine, vol. 153, p. 106854, Dec. 2021, doi: https://doi.org/10.1016/j.ypmed.2021.106854

[4]A. Bajaj, “ARIMA & SARIMA: Real-World Time Series Forecasting,” neptune.ai, May 11, 2021. https://neptune.ai/blog/arima-sarima-real-world-time-series-forecasting-guide
‌
[5]GeeksforGeeks, “SARIMA (Seasonal Autoregressive Integrated Moving Average),” GeeksforGeeks, Nov. 17, 2023. https://www.geeksforgeeks.org/sarima-seasonal-autoregressive-integrated-moving-average/
‌
