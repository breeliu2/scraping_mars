# scraping_mars

## This module focused on using our knowledge of web scraping to extract HTML code for 2 Jupyter notebooks. 
Deliverable 1 - scrape titles and preview text from Mars news articles
Deliverable 2 - Scrape and analyze Mars weather data, which exists in a table. 

## Part 1: Scrape Titles and Preview Text from Mars News
Automated browsing with Splinter was used to visit the Mars news site. HTML code was extracted using Beautiful Soup. 
The titles and preview text of the news articles were scraped and stored in a list of dictionaries. 
 {'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
 'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
 
 ## Part 2: Scrape and Analyze Mars Weather Data
 Used Splinter and Beautiful Soup to scrape the data
 The HTML table was extracted into a Pandas DataFrame, which was created with all columns from the website. 
 
 <img width="436" alt="Screenshot 2023-05-18 at 4 54 04 PM" src="https://github.com/breeliu2/scraping_mars/assets/124847109/0f89d0f0-c023-4305-9f5c-a6dbc09ae505">
 
 
 Use the Pandas DataFrame to answer the following questions: 
 * How many months exist on Mars?
 * How many Martian (and not Earth) days worth of data exist in the scraped dataset?
 * What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    - Find the average minimum daily temperature for all of the months.
    - Plot the results as a bar chart.
    - ![image](https://github.com/breeliu2/scraping_mars/assets/124847109/cc3e1929-6bdd-4fa7-86b6-5d3f6a95eca4)
    - The coldest month in Curiosity's location is 3 and the hottest month in Curiosity's location is 8.
   
 * Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    - Find the average daily atmospheric pressure of all the months.
    - Plot the results as a bar chart.
    - ![image](https://github.com/breeliu2/scraping_mars/assets/124847109/237c8cb6-2eeb-45d0-a287-a3ce074a5a71)
    - Month 6 has the lowest atmospheric pressure on Mars and month 9 has the highest atmospheric pressure. 
 
 * About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    - Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    - Visually estimate the result by plotting the daily minimum temperature.
    - ![image](https://github.com/breeliu2/scraping_mars/assets/124847109/00c1907c-161a-4efd-a8f6-515907fa506f)
    - There is an estimated 680 Earth days in one Martian year by looking at the graph. The internet confirms that one Mars year is equal to 687 Earth days.  
    




