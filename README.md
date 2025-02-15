# NASA's mars-news
web site: https://static.bc-edx.com/data/web/mars_news/index.html
          https://static.bc-edx.com/data/web/mars_facts/temperature.html
          
part 1 Scrape Titles and Preview Text from Mars News

we are working on this code and the steps below to scrape the Mars News website.
We create a Beautiful Soup object and use it to extract text elements from the website.
Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
 -Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.

 Part 2: Scrape and Analyze Mars Weather Data

 We create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.

we are going to Assemble the scraped data into a Pandas data frame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

   id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location

We examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
We analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature of each observation.
