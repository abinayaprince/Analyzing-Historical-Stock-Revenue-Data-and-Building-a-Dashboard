Tesla & GameStop Stock and Revenue Data Analysis
This project focuses on extracting, cleaning, and visualizing stock and revenue data for Tesla (TSLA) and GameStop (GME) using Python libraries such as yfinance, pandas, requests, and matplotlib. It includes web scraping, data preprocessing, and data visualization.

✅ Questions Covered
Question 1: Extract Tesla Stock Data using yfinance

Used yfinance.download() to fetch Tesla stock data.
Reset the index of the DataFrame.
Displayed the first 5 rows using head().
--------------------------------------------------------------------------------------------
Question 2: Extract Tesla Revenue Data using Web Scraping
Scraped Tesla quarterly revenue data from macrotrends.net.

Used requests, BeautifulSoup, and pandas.
Cleaned the data and removed any missing or null values.
Displayed the last 5 rows using tail().
-----------------------------------------------------------------------------------------------
Question 3: Extract GameStop (GME) Stock Data using yfinance

Fetched GME stock data.
Reset the index and displayed the first 5 rows.

------------------------------------------------------------------------------------------------
Question 4: Extract GameStop Revenue Data using Web Scraping

Scraped GME revenue data from macrotrends.net.
Parsed the correct table using BeautifulSoup.
Displayed the last 5 rows after data cleaning.

--------------------------------------------------------------------------------------------------
Question 5: Plot Tesla Stock Data


Defined a reusable function make_graph() using matplotlib.
Visualized Tesla stock closing prices over time.

------------------------------------------------------------------------------------------------------------
Question 6: Plot GameStop Stock Data


Reused the make_graph() function.
Plotted GME stock closing prices.
-----------------------------------------------------------------------------------------------------------------------
