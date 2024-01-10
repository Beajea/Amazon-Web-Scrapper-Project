# Amazon-Web-Scrapper-Project

This Python project utilizes web scraping techniques to extract product information, such as title and price, from an Amazon product page. The data is then stored in a CSV file for tracking changes over time. The script also includes a functionality to send email notifications when the price drops below a certain threshold.

Project Structure:
web_scraper.py: The main Python script containing functions to scrape Amazon product data, clean the data, and store it in a CSV file. It also includes the functionality to send email notifications.

AmazonWebScraperDataset.csv: CSV file to store the scraped data, including product title, price, and the date of extraction.

email_notification.py: A script for sending email notifications when the price drops below a specified level.

Dependencies:
BeautifulSoup: For parsing HTML content.

requests: For making HTTP requests to the Amazon product page.

smtplib: For sending email notifications.

time: For introducing delays in the script to avoid overloading the server.

How to Use:
Clone the repository: git clone https://github.com/your-username/amazon-web-scraper.git
Install dependencies: pip install -r requirements.txt
Run the web_scraper.py script to start scraping and tracking product data.
