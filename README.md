# <a href= "https://colab.research.google.com/drive/1zyrccgZwTn0XQYH9eMH5AzLfCrUXjiu_?usp=sharing"  target="_blank"> Crawling Data on the Top 10 Most Popular Stocks </a>
<a href="https://colab.research.google.com/drive/1zyrccgZwTn0XQYH9eMH5AzLfCrUXjiu_?usp=sharing" target="_blank">View in Colab by clicking the link</a>

Crawling Data on the Top 10 Most Popular Stocks (as of November 2024) from South Korea's Largest Financial Web Portal https://finance.naver.com/. 

## **Introduction**
The goal of this project is to retrieve data on key financial indicators for the ten most-searched stocks listed on finance.naver.com.

## **About the Website to be scrapped**
As one of South Korea's largest financial web portal,  finance.naver.com provides a wealth of financial and stock market data, serving as a resource for investors and analysts.

## **Project Scope**
This project uses web crawling techniques to retrieve the KOSPI stock codes of the ten most-searched stocks on Naver Finance, along with their corresponding key financial indicators published on the platform. The extracted tables include critical financial metrics such as income, profit, return on investment (ROI), and other essential indicators for assessing corporate performance.

## **Workflow**
The project follows these steps to extract and process financial data:
1. Utilize the pandas library's read_html() function to scrape data from finance.naver.com.
2. Identify and fetch data for the ten most-searched stocks on the platform.
3. Retrieve the complete list of KOSPI-listed companies using the StockListing() function from the finance-datareader library.
4. Match the stock codes of the ten most-searched companies with the KOSPI-listed companies' table.
5. Translate the name of financial indicators from Korean in English
6. Extract the key financial indicators for these 10 companies from finance.naver.com.
