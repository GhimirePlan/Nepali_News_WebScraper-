# Nepali News Web Scraper  

This repository contains a **Python-based web scraper** designed to extract news articles from popular Nepali news portals, including **eKantipur**, **Annapurna Post**, **Kathmandu Post**, and **Nepal Fact Check**. It collects article headings, subheadings, and URLs, saving them to an Excel file for further analysis or development of custom news aggregation platforms.  

## Features  
- Scrapes article headings (`<h2>`), subheadings (`<p>`), and associated URLs.  
- Supports scrolling for dynamically loaded content to extract large datasets.  
- Exports data into a structured Excel file (`.xlsx`).  
- Headless browser setup to run the scraper without opening the browser window.  
- Error handling and configurable data extraction limits.  

## Requirements  
Ensure the following dependencies are installed before running the scraper:  
- **Python 3.8+**  
- **Google Chrome**  
- **ChromeDriver**  
- Python Libraries:  
  - `selenium`  
  - `bs4` (BeautifulSoup)  
  - `openpyxl`  

## Setup  
1. Clone the repository:
   ```bash 
   git clone https://github.com/GhimirePlan/Nepali_News_WebScraper-.git
   cd nepali-news-web-scraper
3. Install the required Python libraries:
   ```bash 
   pip install selenium beautifulsoup4 openpyxl
5. Download and place the appropriate ChromeDriver in your system.
    Ensure it matches your installed Chrome version.
    Update the driver_path in the script with the correct path to chromedriver.
## Usage
1. Update the url variable with the URL of the news portal you want to scrape.
2. Configure max_data to limit the number of articles to extract.
3. Run the script:
   ```bash 
   python file_name.py
5. The scraped data will be saved in an Excel file(.xlsl) in the project directory.

## Supported News Portals
  - eKantipur
  - Annapurna Post
  - Kathmandu Post
  - Nepal Fact Check
  
## Keywords
Nepali news scraper, eKantipur scraper, Annapurna Post data extraction, Kathmandu Post crawler, Nepali journalism analysis, Selenium web scraping, BeautifulSoup scraping


