# CodeAlpha_WebScraping
CodeAlpha Internship Web Scraping project

This project involves the development of a professional web scraper using Python to extract structured data from an online bookstore. The goal was to demonstrate the ability to navigate complex HTML structures, handle pagination, and perform data cleaning for further analysis.
###################################

The objective of this task was to:

Extract data from a website using Python libraries.

Handle multi-page navigation (Pagination).

Clean and transform raw HTML data into a structured format (Pandas DataFrame).

Prepare a dataset for potential future Exploratory Data Analysis (EDA).

###################################
The scraper targets Books to Scrape, a site designed for testing scraping logic. The final dataset includes information for 1,000 books across 50 different categories.
###################################
Scraped Features:

    Title: The full name of the book.
    
    Price: Extracted as a float (currency symbols removed).
    
    Rating: Converted from text (e.g., "Three") to a numerical scale (1-5).
    
    Category: The genre/category the book belongs to.
###################################
Technologies Used
Python 3.x

BeautifulSoup4: For parsing HTML content.

Requests: For handling HTTP protocol and fetching web pages.

Pandas: For data manipulation and structured storage.

Regular Expressions (re): For cleaning price strings.
