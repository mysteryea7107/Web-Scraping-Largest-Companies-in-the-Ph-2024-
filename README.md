Web Scraping: Largest Companies in the Philippines (2024)

Welcome to my web scraping project! This repository contains Python scripts utilizing Beautiful Soup to extract data about the largest companies in the Philippines directly from Wikipedia.

Project Overview

The goal of this project is to practice and demonstrate web scraping techniques using Python's BeautifulSoup and requests libraries. The script parses HTML content from a Wikipedia page detailing the largest corporations in the Philippines, cleans the extracted data, and organizes it for analysis.

Repository Structure

├── notebooks/
│   └── web_scraping_largest_companies.ipynb  # Jupyter Notebook containing the scraper and data processing steps
├── data/
│   └── source_link.txt                       # Text file containing the target Wikipedia URL
└── README.md                                 # Project documentation


Technologies Used

Python 3.x

Beautiful Soup 4 (bs4) - For parsing HTML and navigating the parse tree.

Requests - For making HTTP GET requests to fetch the Wikipedia page.

Pandas - For structuring, cleaning, and exporting the scraped tabular data.

Jupyter Notebook - Interactive development and execution environment.

Target Source

The link to the Wikipedia page being scraped is stored in data/source_link.txt.

How to Run

Clone the repository or download the files.

Install the required dependencies:

pip install beautifulsoup4 requests pandas jupyter


Navigate to the notebooks/ directory and launch Jupyter Notebook:

jupyter notebook


Open web_scraping_largest_companies.ipynb and run the cells sequentially to fetch, parse, and view the scraped data.

Key Learnings & Features

Inspecting HTML structures using browser developer tools.

Locating specific tables on Wikipedia using CSS selectors and attributes (e.g., class="wikitable").

Iterating through table rows (<tr>) and cells (<th>, <td>) to extract text data.

Handling data cleaning tasks (e.g., stripping whitespace, removing reference citations, and converting string numbers into numerical formats).

Author

Created as part of my data science and web scraping learning journey!
