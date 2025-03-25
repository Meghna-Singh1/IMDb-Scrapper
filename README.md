# IMDb-Scrapper
International Movie Database Web Scrapper

## Overview
This IMDb Scraper extracts data about the **Top 100 Movies** based on IMDb user ratings. It fetches details such as movie title, release year, runtime, IMDb rating, Metascore, number of votes, and gross collection, then stores them in a structured CSV file.

## Features
- Scrapes IMDb's Top 100 movies.
- Extracts relevant movie details.
- Saves data in CSV format.

## Technologies Used
- **Python**: For scripting the scraper.
- **BeautifulSoup**: For parsing HTML content.
- **Requests**: For making HTTP requests.
- **Pandas**: For handling and saving data.
- **NumPy**: For numerical operations.

## Installation
### Prerequisites
Make sure you have Python installed on your system. You can install the required libraries using:

```sh
pip install requests beautifulsoup4 pandas numpy
```

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/imdb-scraper.git
   cd imdb-scraper
   ```
2. Run the script:
   ```sh
   python imdb_scraper.py
   ```
3. The scraped data will be saved as `Top_100_IMDB_Movies.csv` in the project directory.

## Output
The output CSV file contains the following columns:
- **Name of Movie**
- **Year of Release**
- **Watchtime (Minutes)**
- **IMDb Rating**
- **Metascore**
- **Votes**
- **Gross Collection**

## Example Output
```
| Name of Movie   | Year of Release | Watchtime | IMDb Rating | Metascore | Votes  | Gross Collection |
|----------------|----------------|-----------|-------------|-----------|--------|------------------|
| The Shawshank Redemption | 1994 | 142 | 9.3 | 80 | 2,500,000 | $28.3M |
| The Godfather | 1972 | 175 | 9.2 | 100 | 1,800,000 | $134.9M |
```

