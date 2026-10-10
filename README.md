# scrap_dash_task
# GitHub Trending Repositories Dashboard
## Project Overview
An interactive web application that scrapes live trending GitHub repositories and visualizes star counts and programming language distributions[cite: 2, 3].
## Data Source
Scraped directly from [GitHub Trending](https://github.com/trending) using BeautifulSoup[cite: 1, 3].
## Dashboard Features
- 4 KPI Cards (Total Repositories, Total Stars, Top Language, Average Stars)[cite: 3]
- 2 Charts (Top 10 repositories bar chart & Language distribution pie chart)[cite: 3]
- Interactive Programming Language Dropdown Filter[cite: 3]
## Instructions to Run
1. Install dependencies: `pip install dash plotly pandas requests beautifulsoup4 lxml`
2. Run the scraper: `python scraper.py`
3. Run the dashboard: `python app.py`
4. Open `http://127.0.0.1:8051/` in your browser.
