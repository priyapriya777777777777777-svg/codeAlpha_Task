# Task 1 - Web Scraping

## Objective

The objective of this task is to collect book information from a website using Python web scraping techniques and create a structured dataset.

## Website

Books to Scrape

https://books.toscrape.com/

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas

## Data Collected

- Book Title
- Price
- Rating
- Availability

## Methodology

1. Send HTTP requests to the website.
2. Retrieve the HTML content.
3. Parse the HTML using BeautifulSoup.
4. Extract book details.
5. Clean the collected data.
6. Store the data in a Pandas DataFrame.
7. Export the final data as a CSV file.

## Result

A dataset containing 1000 book records was successfully collected and saved as `books_dataset.csv`.

## Files

- `CodeAlpha_WebScraping.ipynb` - Web scraping code
- `books_dataset.csv` - Scraped dataset
