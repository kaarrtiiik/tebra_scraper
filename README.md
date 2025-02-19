Tebra Physical Therapist Data Scraper

This Python script scrapes data of Physical Therapists from Tebra.com. It extracts provider information and saves it as a JSON file.

Features
Asynchronously scrapes provider data.
Extracts name, company, locations, phone, and website.
Handles pagination to scrape multiple pages.
Saves data to providers.json.
Dependencies
Install required Python libraries:

Bash

pip install aiohttp beautifulsoup4 lxml pandas
aiohttp
asyncio
beautifulsoup4
lxml
pandas
Usage
Run the script from your terminal:

Bash

python tebra_scraper.py
Output
providers.json: JSON file containing scraped data. Example:
JSON

[
    {
        "Provider Name": "...",
        "Company Name": "...",
        "Number of Locations": ...,
        "Location Address": ["...", "..."],
        "Phone Number": "...",
        "Website Link": "[https://www.tebra.com/...](https://www.google.com/search?q=https://www.tebra.com/...)"
    },
    ...
]
