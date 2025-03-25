# IMDb-Scrapper
International Movie Database Web Scrapper

## Overview
This project is a web scraper that extracts movie details from IMDb's top-rated movies list. It uses Python with BeautifulSoup and Requests to fetch and parse movie data, storing it in a CSV file for analysis.

## Features
- Scrapes movie names, release years, runtime, ratings, metascore, votes, and gross collections.
- Uses BeautifulSoup for HTML parsing and Requests for web requests.
- Saves data in a structured CSV format for easy access and analysis.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/imdb-scraper.git
   ```
2. Navigate to the project directory:
   ```sh
   cd imdb-scraper
   ```
3. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the script:
   ```sh
   python imdb_scraper.py
   ```
2. The scraped data will be saved as `Top_100_IMDB_Movies.csv` in the project directory.

## Output Format
The script generates a CSV file with the following columns:
- **Name of movie**: Title of the movie
- **Year of release**: Year the movie was released
- **Watchtime**: Duration of the movie in minutes
- **Movie Rating**: IMDb rating
- **Metascore**: Metacritic score
- **Votes**: Number of IMDb votes
- **Gross collection**: Box office revenue (if available)

## Example Output (CSV Preview)
| Name of movie | Year of release | Watchtime | Movie Rating | Metascore | Votes | Gross collection |
|--------------|----------------|-----------|--------------|-----------|-------|------------------|
| The Shawshank Redemption | 1994 | 142 | 9.3 | 80 | 2,500,000 | $28M |
| The Godfather | 1972 | 175 | 9.2 | 100 | 1,800,000 | $134M |

## Dependencies
- `pandas`
- `requests`
- `beautifulsoup4`
- `numpy`
