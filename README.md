# Amazon Price Tracker

## Overview
This Amazon Price Tracker is a Python-based application with a PyQt5 GUI that allows users to track price changes of products on Amazon. It uses Selenium and BeautifulSoup to scrape product details and notifies users via email when the price drops below a specified amount.

## Features
- User-friendly GUI built with PyQt5.
- Scrapes Amazon product details including title and price.
- Sends email notifications when the price falls below the user-defined threshold.
- Input validation for URL, price, and email.

## Requirements
Ensure you have the following dependencies installed before running the application:

```sh
pip install PyQt5 selenium webdriver-manager beautifulsoup4 requests lxml smtplib
```

## Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/amazon-price-tracker.git
   cd amazon-price-tracker
   ```
2. Run the application:
   ```sh
   python main.py
   ```

### How to Use
1. Enter the Amazon product URL.
2. Set the target price at which you want to receive an alert.
3. Enter your email address to receive notifications.
4. Click the "Check Price" button.
5. If the price drops below your target, an email alert will be sent.

## Email Notifications
The application uses an SMTP server to send email alerts. Make sure you have an internet connection and enter a valid email address to receive notifications.

## Legal & Ethical Considerations
- This tracker is for personal and educational use only.
- Scraping Amazon may violate their Terms of Service. Use responsibly.
- Avoid excessive requests to prevent being blocked by Amazon.

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change
