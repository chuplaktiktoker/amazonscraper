Amazon Scraper
This is a Python web scraping project that extracts product information from Amazon. The scraper utilizes the BeautifulSoup library to parse HTML and extract data from product listings on Amazon's website.

Features
Scrape product details such as title, price, rating, and description.
Extract additional information such as product images, customer reviews, and seller information.
Ability to search for specific products by keyword and category.
Supports pagination to scrape multiple pages of search results.
Save scraped data to a CSV file for further analysis or integration with other systems.

Requirements
Python 
BeautifulSoup library 
Requests library 
CSV library

1.Usage
Clone the repository:
git clone https://github.com/chuplaktiktoker/amazon-scraper.git

Install the required dependencies:
pip install -r requirements.txt

2. Customize the scraper parameters, such as the search keyword and category, in the config.py file.

Run the scraper:
python scraper.py
The scraped data will be saved to a CSV file named output.csv.

Notes
This scraper is intended for educational and personal use only. Please ensure that your scraping activities comply with Amazon's terms of service and legal guidelines.
The code is provided as-is and may require modifications to adapt to changes in Amazon's website structure.
