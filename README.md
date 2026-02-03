# EDA-Project
Performed web scraping and exploratory data analysis on Flipkart Smart TV listings to analyze pricing trends, brand positioning, and customer engagement. Extracted real-world e-commerce data using Python and Selenium to identify value-for-money products and key factors influencing price and popularity.

---

# Analysis of Smart TV Pricing and Customer Engagement on Flipkart

## Project Overview

This project analyzes Smart TV pricing and customer engagement on the Flipkart e-commerce platform using web scraping and Exploratory Data Analysis (EDA). Real-world product data was collected from Flipkart to identify pricing patterns, brand positioning, and customer behavior.

The analysis helps both customers and sellers make data-driven decisions by understanding how price, screen size, and features influence customer engagement.

---

## Business Problem

* Customers find it difficult to identify value-for-money Smart TVs due to a wide range of choices.
* Sellers lack clear insights into pricing trends and customer preferences.
* The relationship between TV size and price is not clearly quantified.
* Customer engagement through ratings and reviews is not well understood in relation to pricing.

---

## Objectives

* Collect Smart TV product data from Flipkart using web scraping
* Clean and preprocess raw scraped data
* Extract key features such as brand, screen size, price, and specifications
* Analyze pricing trends across different TV sizes and brands
* Study customer engagement using ratings and reviews
* Apply exploratory data analysis and hypothesis testing
* Support data-driven decision-making for customers and sellers

---

## Tools and Technologies Used

* Python
* Selenium
* BeautifulSoup
* Pandas
* Matplotlib
* Seaborn

---

## Dataset Description

* Source: Flipkart Smart TV product listings
* Scope: Analysis of multiple Smart TV brands, prices, screen sizes, and specifications

### Key Features

* Product Information: TV name, brand name
* Pricing Details: Price (INR)
* Technical Specifications:

  * Screen size (inches)
  * Resolution (HD, Full HD, Ultra HD)
  * Display type (LED, QLED, OLED)
  * Smart TV availability
* Customer Engagement Metrics:

  * Ratings count
  * Reviews count
* Derived Feature:

  * Price per inch (used to measure cost efficiency)

---

## Web Scraping Methodology

* Scraped Smart TV data from Flipkart using Selenium for dynamic content
* Extracted product name, brand, price, size, and customer reviews
* Cleaned and structured raw data
* Stored the processed data in CSV format
* Prepared the dataset for exploratory data analysis

---

## Data Cleaning and Preprocessing

* Removed irrelevant text and formatting from product names
* Extracted brand names and screen sizes using regular expressions
* Converted price, ratings, and reviews to numeric values
* Handled missing values and removed incomplete records
* Standardized categorical variables
* Removed duplicate entries
* Created derived features for analysis

---

## Exploratory Data Analysis

### Brand Market Share

* Market leaders include Foxsky, Blaupunkt, and Panasonic
* Brands such as Xiaomi, Thomson, and realme offer strong value-for-money options
* Premium brands like Samsung, LG, and Sony focus on higher-priced segments
* The market is competitive with brand concentration across segments

### Pricing and Size Analysis

* Strong positive correlation between TV size and price
* Larger screen sizes generally lead to higher prices

### Customer Engagement Analysis

* Weak relationship between price and customer ratings or reviews
* Strong correlation between ratings count and reviews count
* Mid-range TV sizes (32–43 inches) receive higher customer engagement

---

## Multivariate Analysis

* TV size and price show a strong positive correlation
* Price has little influence on customer engagement
* Ratings and reviews are strongly correlated, validating engagement metrics

---

## Hypothesis Testing

* Test used: Pearson correlation
* Significance level: 0.05

### Hypothesis 1: TV Size vs Price

* Result: Statistically significant
* Conclusion: TV size has a significant impact on price

### Hypothesis 2: Price vs Customer Engagement

* Result: Not statistically significant
* Conclusion: Price does not significantly influence customer engagement

---

## Conclusion

* Screen size is the primary driver of Smart TV pricing
* Customer engagement depends more on value and features than price
* Ratings and reviews are reliable indicators of product popularity
* Data-driven analysis helps identify value-for-money products

---

## Future Scope

* Perform time-based price trend analysis
* Apply sentiment analysis on customer reviews
* Extend analysis to other e-commerce platforms
* Build a recommendation system for Smart TVs

---

## Author

A. Vinay Reddy
Batch – 456

---


