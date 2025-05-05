# Auction-Data-Scraper

This Python script automates the login and data extraction process from an auction site using Selenium and BeautifulSoup. It logs in, navigates to an auction page, and extracts bidding metrics such as bidder count, bid values, and estimated price ranges.

## 🔧 Features

- Automates login using Selenium WebDriver
- Navigates to a specific auction lot
- Extracts:
  - Number of active bidders
  - Total bids
  - Current bid value
  - Bid percentage
  - Low and high estimate values
- Parses data using BeautifulSoup
- Modular structure for easy reuse and integration
- Save the data to a csv file (loading..........)
- Email the csv file to you (loading............)

## 🚀 Technologies Used

- Python 3.x
- Selenium
- BeautifulSoup
- Firefox WebDriver (GeckoDriver)

## 📦 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/bidsquare-scraper.git
   cd bidsquare-scraper
