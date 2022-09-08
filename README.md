# habr-scraper

Code for scraping Python code snippets from [Habr](https://habr.com) posts.

Instructions:

- run `poetry install` to set up an envirpnment and install dependencies
- run `poetry run python habr_scraper/scraper.py --fetch` to fetch IDs of Habr posts with Python code
- run `poetry run python habr_scraper/scraper.py --download` to download Python snippets from the fetched post IDs
