# Web Scraping Project

This project contains a Jupyter notebook (`API_web_scraping.ipynb`) demonstrating various web scraping techniques using Python.

## Contents

### 1. Weather API Fetching
- Fetches current weather data for Dhaka from the Open-Meteo API.
- Saves the data to a JSON file (`weather_dhaka.json`).

### 2. Quote Scraping
- Scrapes quotes and authors from http://quotes.toscrape.com.
- Saves the extracted data to a JSON file (`quotes.json`).

### 3. News Headlines Scraping with Selenium
- Uses Selenium to scrape headlines from Prothom Alo Bangladesh section (https://www.prothomalo.com/bangladesh).
- Extracts up to 15 headlines with links.

### 4. Archive Headlines Scraping
- Scrapes headlines from a specific date archive on Prothom Alo using requests and BeautifulSoup.
- Allows specifying a fixed date for scraping.

## Requirements

- Python 3.x
- requests
- beautifulsoup4
- selenium
- webdriver-manager
- jupyter

Install dependencies:
```
pip install requests beautifulsoup4 selenium webdriver-manager jupyter
```

## Usage

1. Open the notebook in Jupyter:
   ```
   jupyter notebook API_web_scraping.ipynb
   ```

2. Run the cells in order to execute the scraping scripts.

## Notes

- Ensure compliance with the terms of service and robots.txt of the websites being scraped.
- Website structures may change over time, requiring updates to the scraping code.
- For Selenium scraping, ChromeDriver is managed automatically via webdriver-manager.

## License

[Add your license here if applicable]
