**Odisha RERA Project Scraper**

Overview

This Python project automates the extraction of real estate project and promoter details from the Odisha RERA website. Using Selenium for browser automation and BeautifulSoup for parsing HTML, the scraper visits individual project pages, collects key information, and saves it in a CSV file for easy analysis.

**Features**

Scrapes project details including:
Project Name
RERA Registration Number
Scrapes promoter details including:
Company Name (or Proprietor Name)
Registered Office Address (or Current Residence Address)
GST Number
Navigates through project listings and promoter tabs dynamically
Handles variations in field labels with fallback matching
Saves extracted data in a structured CSV file
Uses Safari WebDriver for macOS browser automation

**Technologies Used**

Python 3
Selenium WebDriver
BeautifulSoup 4 (bs4)
CSV module (built-in)

**Setup & Installation**


Install required Python packages:
pip install selenium beautifulsoup4

Enable Safari WebDriver (macOS only):
Open Terminal and run:

safaridriver --enable
Run the scraper script:
python rera_scraper.py

**Output**

The scraper outputs a CSV file named odisha_rera_projects.csv containing the following columns:

| Project Name | RERA Regd. No. | Company Name | Registered Office Address | GST No. |
