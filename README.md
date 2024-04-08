Amazon Product Price Tracker

This Python script is designed to track the price of a specific product on Amazon using web scraping techniques. It fetches the product's title, current price, and date of the data collection, storing this information in a CSV file for analysis and monitoring.

Features

Web Scraping: Utilizes BeautifulSoup and Requests libraries to scrape product information from Amazon's website.
Data Storage: Saves the scraped data including product title, price, and date into a CSV file (AmazonWebScraperDataset.csv).
Automated Price Tracking: Runs periodically to check and update the product price in the CSV file.
Optional Email Notification: Includes a function (send_mail) to send an email notification when the product price drops below a certain threshold (uncomment and configure the function as needed).
Installation

Clone or download the repository to your local machine.
Ensure you have Python 3.x installed along with the required libraries (BeautifulSoup, requests, pandas, smtplib).
Configure the script with your desired Amazon product URL, email credentials (for notification), and price threshold (if using email notification).
Run the script (AmazonPriceTracker.py) using Python.
Usage

Run the script to initiate web scraping and data collection.
The script will periodically check the product price (default interval: 24 hours) and update the CSV file accordingly.
Optionally, configure the email notification function to receive alerts for price drops.
File Structure

AmazonPriceTracker.py: Main Python script containing web scraping, data processing, and price tracking functions.
AmazonWebScraperDataset.csv: CSV file where the scraped data is stored (title, price, date).
README.md: Documentation file explaining the script, its features, installation, and usage instructions.
Dependencies

Python 3.x
BeautifulSoup (bs4)
Requests
Pandas
smtplib (for email notification, if used)
Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.

License

This project is licensed under the MIT License - see the LICENSE.md file for details.
