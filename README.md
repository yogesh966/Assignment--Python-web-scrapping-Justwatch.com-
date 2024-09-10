# Assignment--Python-web-scrapping-Justwatch.com-
### Website:
- JustWatch Movies Url -  https://www.justwatch.com/in/movies?release_year_from=2000
- JustWatch Tv Shows Url - 'https://www.justwatch.com/in/tv-shows?release_year_from=2000'


### Overview
This project involves scraping movie and TV show data from JustWatch, a popular platform that aggregates content from various streaming services such as Netflix, Amazon Prime, Hulu, and more. The scraping is achieved using Python, leveraging the Requests library for HTTP requests and BeautifulSoup for HTML parsing. Instead of utilizing JustWatch APIs, we extract information directly from the HTML structure of the website.

Tasks:
1. Web Scraping:

Use BeautifulSoup to scrape the following data from JustWatch:

a. Movie Information:

  - Movie title
  - Release year
  - Genre
  - IMDb rating
  - Streaming services available (Netflix, Amazon Prime, Hulu, etc.)
  - URL to the movie page on JustWatch
b. TV Show Information:

  - TV show title
  - Release year
  - Genre
  - IMDb rating
  - Streaming services available (Netflix, Amazon Prime, Hulu, etc.)
  - URL to the TV show page on JustWatch
c. Scope:

 ` - Scrape data for at least 50 movies and 50 TV shows.
   - You can choose the entry point (e.g., starting with popular movies,
     or a specific genre, etc.) to ensure a diverse dataset.`
2. Data Filtering & Analysis:

After scraping the data, use Pandas to perform the following tasks:

a. Filter movies and TV shows based on specific criteria:

      - Only include movies and TV shows released in the last 2 years (from the current date).
      - Only include movies and TV shows with an IMDb rating of 7 or higher.
b. Data Analysis:

      - Calculate the average IMDb rating for the scraped movies and TV shows.
      - Identify the top 5 genres that have the highest number of available movies and TV shows.
      - Determine the streaming service with the most significant number of offerings.
3. Data Export:

   - Dump the filtered and analysed data into a CSV file for further processing and reporting.

   - Keep the CSV file in your Drive Folder and Share the Drive link on the colab while keeping view access with anyone.
Submission:

- Submit a link to your Colab made for the assignment.

- The Colab should contain your Python script (.py format only) with clear
  comments explaining the scraping, filtering, and analysis process.

- Your Code shouldn't have any errors and should be executable at a one go.

- Before Conclusion, Keep your Dataset Drive Link in the Notebook.
### Project Workflow
#### 1. Web Scraping: 
Python scripts make HTTP requests to the JustWatch website and use BeautifulSoup to parse the HTML, extracting relevant movie and TV show details.

#### 2. Data Filtering and Analysis:
The scraped data is processed and filtered using Pandas, allowing for in-depth analysis. This stage involves exploring statistics related to the extracted content.

#### 3. Results and Insights:
The analysis provides valuable insights into the available movies and TV shows across different streaming platforms. Results may include popular genres, predominant streaming service, and other relevant observation.

#### 4. Data Export:
The final results are saved to a CSV file, providing a structured format for easy sharing, further analysis, or visualization.

### Technologies Used
- Python
- Requests library for HTTP requests
- BeautifulSoup for HTML parsing
- Pandas for data manipulation and analysis
### Usage
1. Clone the repository to your local machine.
2. Run the provided Python scripts to perform web scraping and data analysis.
3. Explore the generated CSV file containing the results.
   
Feel free to contribute, report issues, or suggest improvements!
