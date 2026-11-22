# Web Scraping Projects

A curated collection of Python scripts and Jupyter Notebooks for extracting structured data from real-world websites across sports, jobs, movies, books, and finance.

## Scrapers Included

| Target / Source | File | Type |
| :--- | :--- | :--- |
| **Wuzzuf** (Job listings) | `wuzzuf_scraper.py` | Python Script |
| **IMDb** (Top 1000 movies) | `imdb_scraper.py` | Python Script |
| **FilGoal** (Match results by date) | `filgoal_scraper.py` | Python Script |
| **Yallakora** (Match center by date) | `yallakora_scraper.py` | Python Script |
| **Wikipedia** (Article text extraction) | `wikipedia_scraper.py` | Python Script |
| **Books to Scrape** | `books_to_scrape.ipynb` | Jupyter Notebook |
| **Rotten Tomatoes** | `rotten_tomatoes_scraper.ipynb` | Jupyter Notebook |
| **Yahoo Finance** | `yahoo_finance_scraper.ipynb` | Jupyter Notebook |

## Tech Stack

- **Language:** Python 3
- **Libraries:** `beautifulsoup4`, `requests`, `lxml`, `pandas`, `numpy`

## Getting Started

```bash
git clone https://github.com/zizo1414/web-scraping-projects.git
cd web-scraping-projects
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Run any individual script, for example:

```bash
python "yallakora_scraper.py"
```

## Disclaimer

For educational purposes only. Respect target websites' `robots.txt` and rate limits.

## License

Licensed under the MIT License — see [LICENSE](./LICENSE) for details.
