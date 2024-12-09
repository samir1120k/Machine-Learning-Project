# IMDB Movie Data Scraper

This project is a web scraper that extracts data about movies from IMDB and saves it into a CSV file. 

## Description

This project uses the `requests` and `BeautifulSoup` libraries in Python to scrape movie data from IMDB, including title, director, rating, genre, cast, year, number of votes, and runtime.

The scraper iterates through a range of IMDB movie IDs, fetches the HTML content of each movie page, parses the HTML using BeautifulSoup, and extracts the desired information.

The extracted data is then stored in a Pandas DataFrame and saved to a CSV file named 'imdb_data.csv'.

## Requirements

* Python 3.6 or higher
* requests library
* beautifulsoup4 library
* pandas library

## Installation

1. Clone the repository:
2. Install the required libraries:
   
## Usage

1. Navigate to the project directory:
2. Run the scraper:

## Output

The scraper will create a CSV file named 'imdb_data.csv' in the project directory. This file will contain the extracted movie data.

## Disclaimer

This project is for educational purposes only. Web scraping should be done responsibly and in accordance with the website's terms of service.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.

