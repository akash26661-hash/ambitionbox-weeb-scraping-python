# ambitionbox-weeb-scraping-python
# AmbitionBox Companies Web Scraping & Analysis (Python)

A Python web scraping project that extracts company listing data from AmbitionBox using `requests` and `BeautifulSoup`, cleans the extracted data with `Pandas`, exports it to a structured CSV dataset, and visualizes top-rated companies.

## Tools & Libraries Used
- **Python**
- **Requests & BeautifulSoup (bs4):** Fetching and parsing HTML DOM elements
- **Pandas:** Data structuring, cleaning, and CSV export
- **Matplotlib:** Visualizing company ratings
- **JupyterLab**

## Extracted Data Fields (8 Columns)
- Company Name
- Rating
- Reviews Count
- Salaries Count
- Interviews Count
- Active Jobs
- Benefits Count
- Photos Count

## Files in this Repository
- `ambitionbox_web_scraping.ipynb` — Complete scraping, cleaning, and visualization notebook
- `ambitionbox_companies.csv` — Final scraped and cleaned dataset
