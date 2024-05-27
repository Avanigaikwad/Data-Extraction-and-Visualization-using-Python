# 📄 **Summary**
This repository contains the source code and documentation for a data analysis project implemented in Python. The project focuses on exploring, analyzing, and visualizing data using various Python libraries and tools.
This repository provides Python scripts and Jupyter notebooks for data extraction from web and visualization tasks. Utilizing popular libraries such as Pandas, Matplotlib, it offers a comprehensive toolkit for analyzing and visualizing data from various sources.

# 📄 Topics Covered
- [Extract stock data using yfinance library](https://github.com/Avanigaikwad/Data-Extraction-and-Visualization-using-Python/blob/main/Data_Extraction_by_yfinance.ipynb)
- [Extract stock data using by web scraping](https://github.com/Avanigaikwad/Data-Extraction-and-Visualization-using-Python/blob/main/Data%20Extraction%20by%20Webscraping.ipynb)
- [Visualizing data and creating Dashboard](https://github.com/Avanigaikwad/Data-Extraction-and-Visualization-using-Python/blob/main/Visualizing%20Stock%20Data.ipynb)

# 🎯 Skills Learned
- Extracting data using yfinance Library
- Webscraping using BeautifulSoup Library
- Exrtracting HTML file using pandas Library
- Data Visualization by matplotlib library

# 📄 Project Description
In this project, we utilized various Python libraries to perform web scraping, data extraction, and visualization of stock data. The primary focus was on extracting historical stock prices and revenue data for Netflix, Amazon, Tesla, and GameStop, and visualizing this data. Below is a summary of the key steps and techniques used:

**Technologies and Libraries Used:**
- **Python Libraries: pandas, requests, BeautifulSoup, yfinance, plotly**
- **Web Scraping Tools: requests, BeautifulSoup**
- **Data Analysis and Visualization: pandas, plotly, yfinance**

**Project Steps and Methodologies:**
1. **Web Scraping Netflix Stock Data:**
   - Sent an HTTP request using the **'requests'** library to fetch the HTML content of a web page containing Netflix stock data.
   - Parsed the HTML content using **'BeautifulSoup'** to isolate and extract relevant data (Date, Open, High, Low, Close, Volume).
   - Stored the extracted data in a pandas DataFrame and printed the first few rows to verify.

2. **Using 'pandas' to Extract Data Directly from Web:**
   - Utilized **'pandas.read_html()'** to directly read HTML tables from web pages into a DataFrame.
   - Demonstrated this with Netflix stock data and verified the extracted data.

3. **Web Scraping Amazon Stock Data:**
   - Followed a similar process as Netflix, using **'requests'** to fetch HTML content and **'BeautifulSoup'** to parse and extract data.
   - Stored the extracted data into a pandas DataFrame.

4. **Using 'yfinance' to Extract Tesla Stock Data:**
   - Used the **'yfinance'** library to create a ticker object for Tesla (TSLA) and extracted historical stock data.
   - Stored the data in a DataFrame and reset the index to make it more readable.

5. **Web Scraping Tesla Revenue Data:**
   - Downloaded and parsed the HTML content of a web page containing Tesla's revenue data.
   - Extracted and cleaned the data, removing unnecessary characters and handling missing values.
   - Stored the cleaned data in a DataFrame and displayed the last few rows to verify.

6. **Using 'yfinance' to Extract GameStop Stock Data:**
   - Created a ticker object for GameStop (GME) and extracted historical stock data using **'yfinance'**.
   - Stored and cleaned the data in a DataFrame, resetting the index for readability.

7. **Web Scraping GameStop Revenue Data:**
   - Parsed the HTML content of a web page containing GameStop's revenue data.
   - Extracted and cleaned the data similarly to Tesla's revenue data.

8. **Visualization of Stock Data:**
   - Defined a function **'make_graph()'** using **'plotly'** to create interactive visualizations of stock prices and revenue data.
   - Visualized the historical share prices and revenue data for Tesla and GameStop, showcasing trends and patterns.

**Conclusion:**

The project demonstrated the practical use of Python for data extraction and visualization. Successfully extracted stock and revenue data from multiple sources using web scraping and the **'yfinance'** library. Additionally, visualized this data using **'plotly'**, providing clear insights into the historical performance of the selected stocks.

This project highlights the power of Python in automating data extraction and creating dynamic visualizations, which are essential skills for data analysis and data science professionals.

# 🎖️ Certificates
![certificate](https://github.com/Avanigaikwad/Data-Extraction-and-Visualization-using-Python/assets/125494847/97397e6d-8bb5-459f-af57-d08e49b60f39)


