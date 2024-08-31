# Project-4_Just-Watch-Movies-Python---Web-Scraping
# Contribution-Individual Surya Singh

# Project Summary:
In this web scraping project, I utilized Python's BeautifulSoup and requests libraries to extract information about movies and tv show from the JustWatch website. The process involved scraping details such as titles, release years, genres, IMDb ratings, age ratings, durations, production countries, streaming service providers, and URLs for both Movies and Tv Shows. I navigated through the HTML structure of the web pages, identifying key elements and their classes to locate the desired information. The code snippets include iterations through lists of movie and TV show URLs, finding specific HTML tags and classes, handling different scenarios such as missing data, and storing the extracted information in Python lists. Subsequently, the data was organized into a Pandas DataFrame, allowing for easy manipulation and analysis. The final DataFrame includes essential details about each movie and TV show, providing a comprehensive dataset for further exploration and insights.
# Website:
JustWatch - https://www.justwatch.com

# Description:
JustWatch is a popular platform that allows users to search for movies and TV shows across multiple streaming services like Netflix, Amazon Prime, Hulu, etc. For this assignment, you will be required to scrape movie and TV show data from JustWatch using Selenium, Python, and BeautifulSoup. Extract data from HTML, not by directly calling their APIs. Then, perform data filtering and analysis using Pandas, and finally, save the results to a CSV file.

# Tasks:
# 1. Web Scraping:

Use BeautifulSoup to scrape the following data from JustWatch:

# a. Movie Information:

  - Movie title
  - Release year
  - Genre
  - IMDb rating
  - Streaming services available (Netflix, Amazon Prime, Hulu, etc.)
  - URL to the movie page on JustWatch
# b. TV Show Information:

  - TV show title
  - Release year
  - Genre
  - IMDb rating
  - Streaming services available (Netflix, Amazon Prime, Hulu, etc.)
  - URL to the TV show page on JustWatch
# c. Scope:

 ` - Scrape data for at least 50 movies and 50 TV shows.
   - You can choose the entry point (e.g., starting with popular movies,
     or a specific genre, etc.) to ensure a diverse dataset.`
# 2. Data Filtering & Analysis:

After scraping the data, use Pandas to perform the following tasks:

# a. Filter movies and TV shows based on specific criteria:

      - Only include movies and TV shows released in the last 2 years (from the current date).
      - Only include movies and TV shows with an IMDb rating of 7 or higher.
# b. Data Analysis:

      - Calculate the average IMDb rating for the scraped movies and TV shows.
      - Identify the top 5 genres that have the highest number of available movies and TV shows.
      - Determine the streaming service with the most significant number of offerings.
# 3. Data Export:

   - Dump the filtered and analysed data into a CSV file for further processing and reporting.

   - Keep the CSV file in your Drive Folder and Share the Drive link on the colab while keeping view access with anyone.
