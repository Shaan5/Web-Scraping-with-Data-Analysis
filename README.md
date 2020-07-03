# Web-Scraping-with-Data-Analysis
This repo will help you to learn how you can scrape data from any website using BeautifulSoup and apply Exploratory Data Analysis on the extracted data for finding useful insights.

## Introduction
Web Scraping (also termed Screen Scraping, Web Data Extraction, Web Harvesting etc.) is a technique employed to extract large amounts of data from websites whereby the data is extracted and saved to a local file in your computer or to a database in table (spreadsheet) format.

## What we are going to do?
Here, the work has been broadly categorized into two steps
1. Scraping data from website
2. Exploratory data analysis

## Scraping data from web

We are going to scrap the data from website using a python library called BeautifulSoup which is mainly used for parsing the html/xml files for scraping the data from it.
For our purpose, we are going to extract data of top 1000 movies from IMDB website.

![imdb_website](https://github.com/Shaan5/Web-Scraping-with-Data-Analysis/blob/master/Web%20Scraping%20with%20Data%20Analysis/data/imdbsite.png)

Each page contains data of only 50 movies, that's why we are going to change the URL parameter through iterating with a set of leap variables of 50 for url extension to parse through next page.

We are going to understand:-
Use of container for parsing?
How data formatting is done and why it is needed?
Why data wrangling is needed?

After parsing, data formatting and data wrangling our final dataset will look like
![dataset](https://github.com/Shaan5/Web-Scraping-with-Data-Analysis/blob/master/Web%20Scraping%20with%20Data%20Analysis/data/dataset.png)

## Exploratory Data Analysis

We are going to perform EDA on the dataset with following steps

**1. Find out the data inconsistancy/missing values**

**2. How to resolve those missing values**

**3. Plotting graphs on the basis of the subsequent data (part of statistical analysis)**

We will understand how to solve the missing values problem with different methods and then finally plotting graphs like
**Swarmplot with seaborn**

![swarmplot](https://github.com/Shaan5/Web-Scraping-with-Data-Analysis/blob/master/Web%20Scraping%20with%20Data%20Analysis/data/swarmplot.png)

**Pie chart**

![pie](https://github.com/Shaan5/Web-Scraping-with-Data-Analysis/blob/master/Web%20Scraping%20with%20Data%20Analysis/data/pie.png)

**Bar Graph**

![bar](https://github.com/Shaan5/Web-Scraping-with-Data-Analysis/blob/master/Web%20Scraping%20with%20Data%20Analysis/data/bar.png)
