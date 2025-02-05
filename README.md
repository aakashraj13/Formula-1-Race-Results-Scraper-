# Formula-1-Race-Results-Scraper-

## Objective: 
   The goal of this project is to scrape the race results for the 2024 Formula 1 season from the official Formula 1 website, process the data, and store it in a structured format (DataFrame). The collected data can then be analyzed for various insights, such as race performance, winning trends, and other factors that influence the outcomes of races
### Technologies Used:
- Python: The primary programming language for scraping, data manipulation, and analysis.
- BeautifulSoup: A Python library for parsing HTML and extracting data from web pages.
- Requests: A simple HTTP library for making requests to the Formula 1 website and fetching the page data.
- Pandas: A powerful data manipulation and analysis library used to store the scraped data in a structured tabular format (DataFrame).
## Dataset 
  The data for this web scraping project is sourced from:
  - **Dataset Link:** [f1 dataset](https://www.formula1.com/en/results/2024/races)
## Project Steps:
  ### Web Scraping Setup:
   - Use requests to fetch the HTML content from the Formula 1 race results page for 2024.
   - Use BeautifulSoup to parse the HTML content and extract relevant sections, such as race names, dates, winners, and times
  ### Data Extraction:
  - Identify and extract the relevant table data, typically contained in <tbody> and <tr> tags.
  - Clean the extracted data by removing extra spaces and non-breaking characters like \xa0.
  ### Data Structuring:
  - Organize the extracted data into a list of lists or DataFrame format using Pandas.
  - Define the appropriate column names (e.g., Race Name, Date, Winner, Team, Time).
  - Populate the DataFrame with the extracted data for each race.
  ### Data Storage:
  - Save the DataFrame into a CSV or Excel file for easy access and further analysis.
## Conclusion
Web scraping proved to be an effective method for extracting real-time race results from the Formula 1 website. By utilizing libraries like BeautifulSoup and Requests, we were able to efficiently parse HTML content and extract relevant race data, such as race names, dates, winners, and teams.Overall, web scraping is a powerful tool for collecting structured data from websites, and when combined with data processing libraries like Pandas, it offers endless opportunities for analysis and insights generation.
  
