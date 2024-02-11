# Mission to Mars
*Challenge 11 of UC Berkeley Data Analytics Bootcamp.*

In this challenge, we collect data/extract information via automated browsing with Splinter and HTML parsing with Beautiful Soup. 
Additionally, we use Python libraries to organize and store data, analyze data, and visually communicate insights.

### Deliveribele 1: Scrape Titles and Preview Text from Mars News
Chrome DevTools was used to identify which elements to scrape and inspect the webpage. A Beautiful Soup object was created and used to extract text elements (titles and preview text of the news articles) from the website. 

The scraped results were extracted as a list of key-value pair dictionaries and stored in a JSON file. See the output folder.
### Deliverable 2: Scrape and Analyze Mars Weather Data
Splinter was imported for automated browsing to visit the Mars Temperature Data Site. Chrome DevTools was used to inspect the page to identify which elements to scrape. A Beautiful Soup object and use it to scrape the data in the HTML table. The scraped data was then assembled into a Pandas DataFrame with the data converted to appropriate data types.

Using Python libraries (Pandas and Matpolotlib) the dataframe was analyzed by answering the following questions:
- What are the coldest and the warmest months on Mars (at the location of Curiosity)? Results were plotted in a bar chart.
- Which months have the lowest and the highest atmospheric pressure on Mars? Results were plotted in a bar chart.
- About how many terrestrial (Earth) days exist in a Martian year? Results were plotted in a Time Series.

The Mars Pandas DataFrame was exported to a CSV_file. See the output folder.

### Summary of Analysis (see part_2_mars_weather.ipynb)
- On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!
- Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.
- The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.