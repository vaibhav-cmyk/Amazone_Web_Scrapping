# Flipkart Product Scraper

This project is a **web scraping script** that extracts product information from Flipkart (or Amazon) using Python. It collects **product names, prices, and discounts** and saves the data into a CSV file.  

## Features
- Scrapes product **name**, **price**, and **discount** from multiple pages.
- Handles pagination automatically until the last page.
- Stores scraped data in a **CSV file** (`amazone_scrab.csv`) for easy analysis.

## Tech Stack
- **Python 3**
- **Requests** – for sending HTTP requests.
- **BeautifulSoup** – for parsing HTML and extracting data.
- **Pandas** – for organizing and saving data to CSV.

## How to Run
1. Install required packages:
   ```bash
   pip install requests beautifulsoup4 lxml pandas
