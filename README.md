# Overview

This project involves web scraping and data analysis to gather information on Mars news and weather patterns. Using Splinter for automated browsing and BeautifulSoup for parsing HTML, the project extracts Mars news headlines and weather data, storing them in structured formats for further analysis.

# Project Components

__1. Scrape Titles and Preview Text from Mars News__: Automated browsing with Splinter to visit the Mars News website. The page was parsed with BeautifulSoup to extract news titles and preview text, which were stored in a list of dictionaries with title and preview keys. Additionally, the data was optionally exported to a JSON file for sharing.

__2. Scrape and Analyze Mars Weather Data__:

Scraped Mars temperature data with Splinter and BeautifulSoup, converting it into a Pandas DataFrame. The dataset was analyzed to examine Mars' months, temperature extremes, atmospheric pressure variations, and the length of a Martian year. Visualizations were created for trends, and the cleaned data was exported to a CSV file.

# Files

__part_1_mars_news.ipynb__: Notebook for scraping Mars news titles and previews.

__part_2_mars_weather.ipynb__: Notebook for scraping and analyzing Mars weather data.

__mars_weather.csv__: Exported DataFrame containing weather data.

# Key Features

__Web Scraping__: Used Splinter for automated browsing and extracted data using BeautifulSoup and structured it in Python dictionaries and Pandas DataFrames.

__Data Analysis__:Analyzed trends in Mars weather using Pandas and Matplotlib while identifying temperature and atmospheric pressure variations. Estimated the number of terrestrial days in a Martian year through visual analysis.

# Dependencies

__Web Scraping__: Splinter, BeautifulSoup, requests.

__Data Handling__: Pandas, JSON.

__Data Visualization__: Matplotlib.

__Jupyter Notebook__: Interactive coding environment.

# Technologies Used

__Python__: Primary programming language.

__Splinter__: Automated browser navigation.

__BeautifulSoup__: HTML parsing and data extraction.

__Pandas__: Data structuring and analysis.

__Matplotlib:__ Data visualization.

__Jupyter Notebook__: Code execution and analysis.

# How to Use

1. Clone this repository to your local machine.

2. Install dependencies using pip install -r requirements.txt.

3. Run part_1_mars_news.ipynb to scrape and store Mars news titles and previews.

4. Run part_2_mars_weather.ipynb to scrape and analyze Mars weather data.

5. Review and visualize the insights extracted from the Mars weather dataset.

<!--Mod 11-->
