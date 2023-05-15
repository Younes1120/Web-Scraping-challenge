# Extracting Mars News and Weather Data Using Web Scraping - Overview
This project aimed to retrieve and analyze news articles and weather data related to Mars through the process of web scraping.

## Purpose

The primary objective of this project was to:

1. Scrape the titles and brief summaries of Mars news articles from websites.
2. Scrape and analyze Mars weather data from an HTML table.

## The following tools and technologies were utilized to achieve the project goals:



Python programming language
Jupyter Notebook
Beautiful Soup library
Splinter library
Pandas library  

## Project Structure

### Part 1: Scraping Mars News
The process for scraping Mars news articles included the following steps:

Automated browsing with Splinter was used to visit the Mars news website.
A Beautiful Soup object was created to parse the HTML content.
Titles and preview text of the news articles were extracted.
The scraping results were stored in a list of dictionaries with 'title' and 'preview' keys.
The list was printed within the Jupyter Notebook.
Optionally, the scraped data was stored in a JSON file for easy sharing.

### Part 2: Scraping and Analyzing Mars Weather Data
Splinter was used for automated browsing to access the Mars Temperature Data Site.
A Beautiful Soup object was created to extract the data in the HTML table.
The extracted data was organized into a Pandas DataFrame with appropriate column headings.
The data types were examined and adjusted to appropriate datetime, int, or float data types as required.
The dataset was analyzed to answer questions related to Martian months, days, temperature, and atmospheric pressure.
The results were visualized using bar charts and line plots.
The DataFrame was exported to a CSV file.

## Conclusion

This project effectively demonstrated the application of web scraping techniques for collecting and analyzing Mars-related news and weather data. The obtained insights offer valuable information on the Martian months, days, temperature, and atmospheric pressure.re.
