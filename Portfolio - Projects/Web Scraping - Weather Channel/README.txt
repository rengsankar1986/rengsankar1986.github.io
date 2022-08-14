Final project:  
As the final project I had the option to either pull data from an open API (other than Twitter, since we have done that in the assignment) or scrape a website and then format the data and do some initial analysis. I could not find an API that I would be able to finish within the given timeline. Hence, I chose to scrape website. 
Choice of websites:
1.	The first website selected for scrapping is http://forecast.weather.gov. I anted to get weather prediction for next seven days for a given latitude and longitude. After getting the data, I wanted to do some data clean up and add meaningful variables to it (e.g. derive temperature is centigrade and show both Fahrenheit and Centigrade).
2.	
Challenges:
1.	As per the requirement I needed to produce a data set with 15-20 variable. But my first scrapped dataset had less variables than that, so I created two different scrapping programs.
2.	Finding a suitable website and getting the HTML object was easy. But scanning through the HTML content and identifying the right tag to start scraping was initially a challenge.
3.	Once the data is retrieved, putting the data in a clean tabular format was a challenge since that needed the proper understanding of the variables.
Learning:
Thorough inspection of the code behind a web page (HTML, CSS etc.) is important to understand the structure and key tags in the web page. Without understanding of this structure, coding a scraping program is difficult.
Is Web Scraping important in Data Science
Web scraping automates acquisition of semi structured data that is hard to interpret, and convert it to human readable format. 
One of the many desired skills of data scientist is, dealing with data sources of different kinds. The internet being a wealthy source of data, websites are very critical data sources for data science projects and data scientists. Ofcourse the usage should abide by best practices and data ethics.

