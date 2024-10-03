# Cryptocurrency-Web-Scrapping-and-Analysis

## Introduction
This project aims to collect and analyze data on the top 10 cryptocurrencies from CoinMarketCap. Using Python, the project extracts data on a weekly basis, starting from April 28, 2013, up until September 29, 2024. The extraction process involves scraping the cryptocurrency data for each specific date and storing it in a DataFrame. The collected data is then transformed through cleaning, formatting, and imputation of missing values. Finally, the project loads the processed data for further analysis. The analysis includes time series analysis, correlation analysis, trend analysis, volatility analysis, comparative analysis, and even predictive analysis. By utilizing web scraping techniques and data analysis tools, this project provides valuable insights into the behavior and performance of the top cryptocurrencies over time.

## Objective
- Collect and Extract Data: Scrape and extract data on the top 10 cryptocurrencies from CoinMarketCap on a weekly basis from April 28, 2013, to September 29, 2024.

- Clean and Format Data: Ensure data accuracy and consistency by performing cleaning and formatting tasks, including handling missing values and standardizing data formats.

- Analyze Cryptocurrency Trends: Identify and analyze trends and patterns in the performance of the top cryptocurrencies, such as price fluctuations, market capitalization, and trading volume over time.

- Predict Future Trends: Utilize the collected data to develop predictive models that can forecast future trends in the cryptocurrency market, aiding in decision-making for investments or trading strategies.

## About the Scraped Dataset
| Column Name       | Description                                                                                |
|-------------------|--------------------------------------------------------------------------------------------|
| Date              | The date on which the data was recorded.                                                   |
| Name              | The name of the cryptocurrency.                                                            |
| Symbol            | The symbol representing the cryptocurrency.                                                 |
| Market Cap        | The total value of all coins of a particular cryptocurrency.                               |
| Price             | The price of a single unit of the cryptocurrency.                                          |
| Circulating Supply| The number of coins that are circulating in the market and are in public hands.             |
| Volume (24hr)     | The total volume of the cryptocurrency traded in the last 24 hours.                        |
| % 1h              | The percentage change in price over the last hour.                                         |
| % 24h             | The percentage change in price over the last 24 hours.                                     |
| % 7d              | The percentage change in price over the last 7 days.                                       |

## Prerequisite
Creating a virtual environment is recommended for projects, and either venv or conda can be used based on personal preference. After creating the virtual environment, it is necessary to activate it before installing any required libraries. This project created a virtual environment called "cantekEnv"

### Tool
- Python (Version: 3.9.6)
- Git (Version: 2.23.0)

Use following command to check version
```
python --version
git --version
```

### Library
Use following command to install the following libraries:
```
pip3 install requests
pip3 install beautifulsoup4
pip3 install requests_html

pip3 install numpy
pip3 install pandas
pip3 install matplotlib
pip3 install tensorflow
```

## Command to run the project:
```
conda activate cantekEnv
jupyter notebook
```

## Scraped Dataset
- [Link](https://github.com/kayhyanki/Cryptocurrency-Web-Scrapping-and-Analysis/blob/f8ca0db598593d8204e38f239304a4edfa115b61/crypto_data_output%20(1).csv)

## Predictive Analysis Result 
![image](https://github.com/user-attachments/assets/6d292e64-fb93-4dfd-9c51-837d0db806ed)
