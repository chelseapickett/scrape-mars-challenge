# scrape-mars-challenge

[Part 1: Scrape Titles and Preview Text from Mars News](https://github.com/chelseapickett/scrape-mars-challenge/blob/main/Starter_Code/part_1_mars_news.ipynb)
The first part of this challenge uses automated browsing to visit the [Mars News site](https://static.bc-edx.com/data/web/mars_news/index.html) where a Beautiful Soup object is used to extract the titles and preview text from the news articles that were scraped from the website. The results were stored in a Python dictionary which were then stored in a list. The final result was printed to show the contents. 

[Part 2: Scrape and Analyze Mars Weather Data](https://github.com/chelseapickett/scrape-mars-challenge/blob/main/Starter_Code/part_2_mars_weather.ipynb)
The second part of this challenge uses automated browsing to visit the [Mars Temperature Data site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) where a Beautiful Soup object is used to extract the data in the HTML table. The extracted data is used to create a Pandas dataframe. The data types were inspected and converted to appropriate data types. The dataset was then analyzed using pandas functions and plotting to answer the following questions: 
- How many months exist on Mars?
- How many Martian days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars?
- Which months have the lowest and the highest atmospheric pressure on Mars?
- About how many terrestrial days exist in a Martian year?

The dataframe was then exported to a csv file which you can view [here](https://github.com/chelseapickett/scrape-mars-challenge/blob/main/Starter_Code/weather_df.csv).

