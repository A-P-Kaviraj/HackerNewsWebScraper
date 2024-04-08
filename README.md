# HackerNews Web Scraper

This is a simple web scraper built in Python to scrape news articles from HackerNews based on the number of votes, filtering those with a vote count higher than 99. It fetches the news title, link, and the number of votes for each article meeting the criteria.

## Requirements

- Python 3.x
- Beautiful Soup 4
- Requests

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/hackernews-scraper.git
    ```
2. Navigate to the project directory:
    ```bash
   cd hackernews-scraper
    ```
3. Install the required dependencies using pip:
    ```bash
   pip install -r requirements.txt
    ```

## Usage

To use the scraper, simply run the hackernews_scraper.py script. It will scrape HackerNews for articles with votes higher than 99 and print out their titles, links, and vote counts.
 ```bash
   python hackernews_scraper.py
 ```

