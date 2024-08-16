# Job Search Web Scraper

## Overview
This project is a Python-based web scraper designed to extract job details from a popular job search website. The scraper utilizes Selenium to handle dynamic content and convert it to HTML, which is then parsed using BeautifulSoup to extract relevant job information.

## Features
- **User Input**: The scraper prompts the user to enter a job role they are interested in.
- **Automated Search**: Selenium automates the search process on the job site based on the user's input.
- **Data Extraction**: The scraper extracts job details such as:
  - Company Name
  - Job Title
  - Ratings
  - Reviews
  - Required Experience
  - Location
- **Data Storage**: Extracted data is stored in a pandas DataFrame, allowing for further analysis and manipulation.

## Technology Stack
- **Selenium**: For automating browser actions and converting dynamic web pages to static HTML.
- **BeautifulSoup**: For parsing HTML and extracting job details.
- **Pandas**: For storing and manipulating the scraped data.

## How It Works
1. **User Input**: The user is prompted to enter the desired job role.
2. **Web Navigation**: Selenium opens a Chrome browser and navigates to the job search website.
3. **Search and Scrape**: The user's input is used to perform a search on the website, and the resulting job listings are scraped.
4. **Data Processing**: The scraped data is parsed and stored in a pandas DataFrame for further analysis.
