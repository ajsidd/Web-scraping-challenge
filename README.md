---

# Module 12 Challenge

This repository contains the solutions for the Module 12 Challenge, which involves web scraping and data analysis related to Mars news and weather data.

## Deliverable 1: Scrape Titles and Preview Text from Mars News

### Step 1: Visit the Website
We utilized automated browsing to visit the Mars news site and inspected the page to identify the elements to scrape.

### Step 2: Scrape the Website
A Beautiful Soup object was created to extract text elements from the website, specifically the titles and preview text of the news articles.

### Step 3: Store the Results
The scraped information was stored in Python data structures, specifically a list of dictionaries, with each dictionary containing the title and preview of a news article.

### Code Snippet
```python
# Code snippet for scraping Mars news titles and preview text
news_dict = {'title': title, 'preview': preview}
```

## Deliverable 2: Scrape and Analyze Mars Weather Data

### Step 1: Visit the Website
Automated browsing was used to visit the Mars Temperature Data Site, and the page was inspected to identify elements for scraping.

### Step 2: Scrape the Table
We created a Beautiful Soup object to scrape the data from the HTML table and assembled it into a Pandas DataFrame.

### Step 3: Store the Data
The scraped data was stored in a Pandas DataFrame with appropriate data types for further analysis.

### Step 4: Prepare Data for Analysis
Data types were examined and converted as necessary for analysis using Pandas functions.

### Step 5: Analyze the Data
We performed analysis on the dataset to answer specific questions related to Martian weather, such as identifying the coldest and warmest months and estimating the length of a Martian year.

### Step 6: Save the Data
The DataFrame was exported to a CSV file for future reference.

### Code Snippet
```python
# Code snippet for scraping and analyzing Mars weather data
df.to_csv(file_path, index=False)
```

---
