# Web-scraping-openpayroll
Public R1 Universities Employment Data Scraper from openpayrolls.com using Selenuim and Undetected Webdriver

## Project Overview
This repository contains a Python-based web scraping project designed to gather employment details of professors from public R1 universities. The project employs a combination of BeautifulSoup, Selenium, and Undetected-Chromedriver to efficiently navigate and extract data from various websites, including Wikipedia and openpayrolls.com.

## Features
- **Wikipedia Scraper**: Extracts a list of public R1 universities using BeautifulSoup.
- **Detailed University Data Scraper**: Uses Selenium and Undetected-Chromedriver to scrape detailed employment data from openpayrolls.com, beginning with the University of Louisiana at Lafayette.
- **Cloudflare Evasion**: Overcomes advanced web defenses like Cloudflare for successful data extraction.
- **Multithreading for Efficiency**: Implements Python's threading to scrape multiple university pages concurrently.

## Installation
To use this scraper, you need to install the required Python libraries. Run the following commands in your terminal: bash
- pip install beautifulsoup4
- pip install requests
- pip install undetected-chromedriver
- pip install selenium
- pip install pandas

## Usage
1. **Scraping R1 Universities List**:
   - Run the Wikipedia scraping script to get the list of R1 universities.
2. **Scraping Individual University Data**:
   - Execute the script for scraping employment details from openpayrolls.com for a specific university.
3. **Scraping Multiple Universities**:
   - Utilize the threading feature to scrape data from multiple universities simultaneously.

## Results
The scripts output detailed employment data of professors in CSV format. An example output file (file-2.csv) is included in the repository, demonstrating the scraper's efficacy.

## Contributing
Contributions to this project are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).

