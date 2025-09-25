# News Headlines Web Scraper (Python)

Scrapes top headlines from Hacker News and saves them into a timestamped `headlines.txt` file using `requests` and `BeautifulSoup`.

## Requirements
- Python 3.9+
- Install: `requests`, `beautifulsoup4`

## Install
```powershell
py -3 -m pip install requests beautifulsoup4
```
If `py -3` doesn’t work, use your Python path:
```powershell
& "C:\Users\<you>\AppData\Local\Programs\Python\Python313\python.exe" -m pip install requests beautifulsoup4
```

## Run
```powershell
py -3 news_scraper.py
```
or
```powershell
& "C:\Users\<you>\AppData\Local\Programs\Python\Python313\python.exe" news_scraper.py
```

This will create/update `headlines.txt` with a header and a numbered list of titles.

## Files
- `news_scraper.py`: Scraper script
- `headlines.txt`: Generated output (created at runtime)
