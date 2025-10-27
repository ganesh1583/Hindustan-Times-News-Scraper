# Hindustan-Times-News-Scraper
Hindustan Times News Scraper

This Python script scrapes the latest headlines from the Hindustan Times website and saves them into a text file named with the current date.

How it works:
Sends a request to the Hindustan Times homepage.
Parses the HTML using BeautifulSoup.
Finds all the latest news items.
Saves them into a text file named as the current date (for example, 2025-10-27.txt).

Requirements:
Python 3
beautifulsoup4 library

Install required library:
pip install beautifulsoup4

Usage:
Clone or download the repository.

Run the script using:
python3 news.py

A new text file will be created with today’s date containing the latest headlines.

Example output:
2025-10-27

News number : 1
India vs England World Cup final today at Ahmedabad
News number : 2
Supreme Court issues notice to Centre over data privacy concerns
The End

Each run creates a new text file with the format YYYY-MM-DD.txt.

Author note:
I created this project back in 2023 and now I’m pushing it to GitHub.
