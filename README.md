# scraping-challenge
DU Data Analysis Module 11 Assignment, Data Collection
Web scraping exercise

## Part 1: Scrape Titles and Preview Text from Mars News
Code is in a jupyter notebook called **part_1_mars_news.ipynb**.

Scrapes the titles and preview text of the news articles on **https://static.bc-edx.com/data/web/mars_news/index.html**. Stores the scraping results in Python list of dictionaries of the form
{"title":"article title",
"preview":"article preview text"}

## Part 2: Scrape and Analyze Mars Weather Data
Code is in a jupyter notebook called **part_2_mars_weather.ipynb**.
Scrapes the weather information table from  **https://static.bc-edx.com/data/web/mars_facts/temperature.html**.
Assembles the scraped data into a Pandas DataFrame with the same columns as the web site and appropriate data types for the data.
Answers the following questions with graphs as illustrations.
* How many months exist on Mars?
* How many Martian (and not Earth) days worth of data exist in the scraped dataset?
* What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
* Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
* About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

