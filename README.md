# Mars web-scrapping_Challenge
This was a comprehensive web scraping and data analysis project focused on Mars-related information. This is a common approach for gathering and analyzing data from websites. The project was broken into two parts:

Part 1: Scrape Titles and Preview Text from Mars News
In this part, I used a combination of Splinter for automated browsing and Beautiful Soup for HTML parsing to extract information from a Mars news website. Specifically, I scraped the titles and preview text of news articles and stored this information in a list of dictionaries. This part of the project involves the following steps:

•	Use Splinter to automate web browsing and navigate to the Mars news site.
•	Extract the HTML code of the webpage using Beautiful Soup.
•	Identify and extract the titles and preview text of news articles.
•	Organize and store this information in a Python data structure, such as a list of dictionaries.

Part 2: Scrape and Analyze Mars Weather Data
In this part, I again focused on scraping and analyzing Mars weather data. I used a combination of Pandas, Splinter, and Beautiful Soup for data extraction and analysis. This part of the project involved the following steps:

•	Extracted the relevant HTML table containing Mars weather data using Beautiful Soup.
•	Converted the extracted data into a Pandas DataFrame with proper headings.
•	Analyzed the data to answer specific questions, such as the number of months on Mars and the number of Martian days' worth of data available.
•	Created data visualizations using matplotlib to support the answers to questions like the average temperature and atmospheric pressure in different months.
•	Estimated the number of terrestrial days in a Martian year, visually, with help of matplotlib by visualizing atmospheric pattern.
•	And finally, exported the data from the DataFrame into a CSV file for further use or sharing.

Overall, this project demonstrates a well-structured approach to web scraping and data analysis, involving both automated web browsing and data manipulation using Python libraries like Beautiful Soup and Pandas. This kind of project can be valuable for gathering and interpreting data from various sources, in this case, Mars-related news and weather information.
