# Ebay_Scraper

This script scrapes product details from eBay's electronics section, extracting key information such as product name, price, shipping cost, and condition. The data is saved to a CSV file for further analysis.

## Features

- Scrapes up to 50 pages of eBay search results for electronics.
- Extracts product details including name, price, shipping cost, and condition.
- Handles different currencies and converts prices to a uniform format.
- Utilizes multiprocessing to speed up the scraping process.
- Saves results to a CSV file.

## Prerequisites

- Python 3.x
- Required Python packages: `requests`, `BeautifulSoup`, `pandas`, `lxml`, `multiprocessing`

You can install the required packages using:

```bash
pip install requests beautifulsoup4 pandas lxml
