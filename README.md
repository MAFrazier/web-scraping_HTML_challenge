# web-scraping_HTML_challenge

## Web-scraping and data analysis project:

### Identifying HTML elements on NASA’s Mars news article webpage and Mars Temperature Data SiteLinks
### Identifying their id and class attributes
### Extraction of information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. 
### Scraping various types of information including HTML tables and recurring elements, and multiple news articles on  provided webpages.

## Project Components:

### Part 1: Scrape titles and preview text from Mars news articles.
    1.	Create a Beautiful Soup object and use it to extract text elements from the website.
    2.	Extract the titles and preview text of the news articles that you scraped. 
        Store the scraping results in Python data structures as follows:
    3.	Store each title-and-preview pair in a Python dictionary and,
        give each dictionary two keys: title and preview. 
    4.	Store all the dictionaries in a Python list.
    5.	Store each title-and-preview pair in a Python dictionary and, 
        give each dictionary two keys: title and preview. 
    6.	Store all the dictionaries in a Python list.

### Part 2: Scrape and analyze Mars weather data, which exists in a table.
    1.	Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site. 
        Inspect the page to identify which elements to scrape. 
    2.	Create a Beautiful Soup object and use it to scrape the data in the HTML table. 
    3.	Assemble the scraped data into a Pandas DataFrame. 
    4.	Examine the data types that are currently associated with each column and 
        convert the data to the appropriate datetime, int, or float data types.
    5.	Analyze your dataset by using Pandas functions to answer the following questions:
          •	How many months exist on Mars?
          •	How many Martian (and not Earth) days worth of data exist in the scraped dataset?
          •	What are the coldest and the warmest months on Mars (at the location of Curiosity)?  
              Plot the results as a bar chart.
          •	Which months have the lowest and the highest atmospheric pressure on Mars? 
              Plot the results as a bar chart.
          •	About how many terrestrial (Earth) days exist in a Martian year? 
          •	Export the DataFrame to a CSV file.
