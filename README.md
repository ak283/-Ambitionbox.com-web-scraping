This is a web scraping based project prototype where Sector, reviews, ratings, employees counts, location of the various companies were collected from www.AmbitionBox.com website and used for data analysis.

For this project python request library is used to scrape the HTML content of the webpage along with BeautifulSoup library to parse the scraped HTML data.

This project follows the following steps:-

Importing all the necessary library like pandas, Numpy, requests, BeautifulSoup.
Creating a request to fetch all the html tags from the AmbitionBox web page.
Parsing the fetched tags using BeautifulSoup library.
Collecting the required company's information using HTML tag
Creating a DataFrame of all the collected data.
Performing data analysis of the collected data.
Exporting the collected data to the csv file.
