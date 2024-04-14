# Stock Prediction Project

## Introduction
This project aims to scrape the latest stock market news from Yahoo Finance and save it in a CSV file for further analysis. The script is written in Python and utilizes the BeautifulSoup library for web scraping.

## Requirements
To run this project, you need the following Python libraries:
- BeautifulSoup (bs4)
- Requests
- Pandas

## Usage
1. Run the `Stock_prediction.ipynb` notebook in a Jupyter environment or any Python environment that supports Jupyter notebooks.
2. Ensure that the notebook has access to the internet to scrape data from Yahoo Finance.
3. Execute the cells in the notebook sequentially to import necessary libraries, define functions, and scrape news data.
4. The scraped data will be saved in a CSV file named `stocknews.csv` in the current directory.

## Structure
- `Stock_prediction.ipynb`: Jupyter notebook containing the code for scraping and saving stock market news.
- `stocknews.csv`: CSV file containing the scraped stock market news data.

## Functions
- `get_webpage(url)`: Retrieves the HTML content of a webpage using its URL and returns a BeautifulSoup object.
- `get_news_tags(doc)`: Extracts a list of <div> tags containing news information from a BeautifulSoup object.
- `parse_news(news_tag)`: Parses individual news <div> tags and returns a dictionary containing news details.
- `scrape_news(url, path=None)`: Scrapes stock market news from Yahoo Finance, saves it in a CSV file, and returns a pandas DataFrame.

## Credits
This project is based on the tutorial available at [Colab Notebook](https://colab.research.google.com/drive/1Bvn3xSaDYVYSusFvpKVdSxuhM6-ubqhT) and was created for educational purposes.

