Euroleague Player Data Scraper & Tableau Dashboard


This project is about practicing web scraping with Python while diving into Euroleague player data. I scraped player stats from 2008-2021 and cleaned the data to build an interactive Tableau dashboard.

Goal

    Web Scraping: Collect Euroleague player stats from 2008-2021 (excluding 2019-2020 due to COVID-19).
    Data Cleaning: Process and prepare the data using pandas for analysis.
    Tableau Dashboard: Visualize player origins (countries, positions) and analyze performance trends over the years.

Why Start from 2008-2009? 🏀

The modern Euroleague format took shape in the 2008-2009 season, introducing a more stable league structure with long-term licenses for teams. This makes it a great starting point for analyzing how the league has evolved over time.

Data Source 🏅

Data is scraped from Eurobasket.com, which publicly provides basic and advanced stats for various basketball leagues around the world.


Tools Used 🔧

    Python (for web scraping & data cleaning)
        requests
        BeautifulSoup
        pandas
        json
    Tableau (for visualization & dashboard creation)

What’s the Dashboard About? 📊

After scraping and cleaning the data, the Tableau dashboard focuses on:

    Player Origins & Positions: Where do Euroleague players come from? Do certain countries produce more guards, forwards, or centers?
    Seasonal Averages: Trends in stats like points, assists, and rebounds over the years.

Credits

Data source: Eurobasket.com 

