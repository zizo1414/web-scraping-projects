# Web Scraping Projects

A curated collection of Python scripts and Jupyter Notebooks for extracting structured data from real-world websites across sports, jobs, movies, books, and finance.

## Scrapers Included

| Target / Source | File | Type |
| :--- | :--- | :--- |
| **Wuzzuf** (Job listings) | `wzzuf scraper.py` | Python Script |
| **IMDb** (Top 1000 movies) | `imdb scrapping.py` | Python Script |
| **FilGoal** (Match results by date) | `filgoal scrapped.py` | Python Script |
| **Yallakora** (Match center by date) | `yallakora scrapping.py` | Python Script |
| **Wikipedia** (Article text extraction) | `wikipedia.py scrapping text.py` | Python Script |
| **Books to Scrape** | `book to scrape.ipynb` | Jupyter Notebook |
| **Rotten Tomatoes** | `rotten tomatoes scrapping .ipynb` | Jupyter Notebook |
| **Yahoo Finance** | `yahoo finance.ipynb` | Jupyter Notebook |

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
python "yallakora scrapping.py"
```

## Disclaimer

For educational purposes only. Respect target websites' `robots.txt` and rate limits.

## License

Licensed under the MIT License — see [LICENSE](./LICENSE) for details.
