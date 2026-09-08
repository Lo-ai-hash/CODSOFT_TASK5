# CODSOFT TASK 5: WEB DATA EXTRACTION & ANALYSIS

## Project Overview

This project focuses on collecting publicly available book data from a website using Python web scraping techniques.

The extracted data was cleaned, organized into a structured dataset, and analyzed to identify pricing patterns, rating distributions, and other useful product insights.

## Objectives

- Collect publicly available data using web scraping
- Extract structured product information
- Clean and organize the collected data
- Perform exploratory data analysis
- Identify trends and patterns
- Export the collected data to CSV
- Generate meaningful business insights

## Website Used

The data was collected from **Books to Scrape**, a publicly available website designed for web scraping practice.

## Data Extracted

The following information was collected for each book:

- Book Title
- Price
- Rating
- Availability

The scraping process was automated across multiple pages to collect a large structured dataset.

## Data Processing

The collected data was cleaned using Pandas.

- Book prices were converted from text to numerical values.
- Rating values were converted from words to numerical scores from 1 to 5.
- Availability text was cleaned.
- Duplicate records were removed.
- The final data was stored in a structured Pandas DataFrame.

## Exploratory Data Analysis

### 1. Price Distribution

A histogram was used to understand the distribution of book prices.

### 2. Rating Distribution

A bar chart was used to analyze the frequency of different book ratings.

### 3. Rating vs Price

A scatter plot was created to examine the relationship between book ratings and prices.

### 4. Most Expensive Books

The top 10 most expensive books were identified using price-based analysis.

### 5. Top-Rated Books

Books with a 5-star rating were identified to understand highly rated products.

## Key Findings

- Most books fall within a moderate price range.
- Book ratings range from 1 to 5 stars.
- Higher ratings do not necessarily mean higher prices.
- Some books have considerably higher prices than the majority of the dataset.
- Highly rated books can be useful for promotional campaigns.
- Price, rating, and availability can be combined to support product-level decisions.

## Business Insights

- Promote highly rated books to attract customers.
- Consider premium marketing strategies for expensive books.
- Use price and rating together when evaluating products.
- Highlight highly rated products in recommendation campaigns.
- Automated web scraping can efficiently collect product information for analysis.

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib
- Google Colab
- GitHub

## Project Files

- `CODSOFT_TASK5_Web_Data_Extraction.ipynb` – Complete web scraping and analysis
- `scraped_books.csv` – Scraped and cleaned book dataset
- `README.md` – Project documentation

## Conclusion

This project demonstrates how Python can be used to automatically extract publicly available web data and transform it into a structured dataset.

The collected book data was cleaned, analyzed, and visualized to identify pricing and rating patterns. The project demonstrates the complete workflow from web data extraction to data analysis and business insights.
