# AmbitionBox_Web_Scraping
Scraped 4000+ company records from AmbitionBox using Python, Requests, and BeautifulSoup, transforming unstructured HTML data into a structured dataset.

# Overview
This project focuses on extracting company data from the AmbitionBox website using Python web scraping techniques. The goal is to collect structured data such as company names, ratings, reviews, salaries, interviews, jobs, and benefits.

# Tech Stack
- Python 
- Pandas 
- Requests 
- BeautifulSoup 

# Dataset Details
The following data fields were extracted:
- Company Name
- Rating
- Number of Reviews
- Salaries
- Interviews
- Jobs
- Benefits

# Features
- Scrapes multiple pages dynamically
- Handles missing data using try-except
- Converts raw HTML into structured DataFrame
- Combines data from multiple pages

# Project Workflow
- Send HTTP request using requests
- Parse HTML using BeautifulSoup
- Extract required elements using class names
- Store data in lists
- Convert lists into Pandas DataFrame
- Merge multiple pages into a single dataset

# Output
- Final dataset shape: 4790 rows
- Structured DataFrame ready for analysis
