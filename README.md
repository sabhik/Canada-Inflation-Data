Canadian Grocery Price Tracker
Project Overview

This project tracks and analyzes Canadian grocery prices by combining web scraping, market-based simulations, and official inflation data from Statistics Canada (CPI).
The goal is to understand how grocery price inflation compares to official CPI numbers and provide store-level insights.

Methodology
Data Collection:

1. Walmart → Prices live scraped (baseline).

2. Metro & Loblaws → Prices simulated when scraping failed (due to bot protection).

Based on Walmart as baseline.

+15–18% multipliers applied to reflect Canadian grocery market positioning.

Small random ±4% variations added to simulate weekly fluctuations.

3. Historical Prices → Generated using Statistics Canada food inflation rates.

Simulation Transparency

All records tagged with data_source:

1. live_scraped (real scrape).

2. market_simulation (Metro/Loblaws).

3. historical_simulation (backfilled CPI trend).

Analysis & Dashboard:

1. Basket Inflation vs StatsCan CPI → Shows how grocery inflation differs from official numbers.

2. Store Comparison → Confirms Walmart as consistently cheaper vs Metro & Loblaws.

3. Product Insights → Identifies key price drivers (e.g., whole chicken, beef).

4. Power BI Dashboard → Clean, storytelling-style visuals highlighting:

a) Basket Inflation (YoY).

b) StatsCan CPI (YoY).

c) Store price comparisons.

d)Product-level drivers.

Tools & Tech Stack:

1. Python → Web scraping (requests, BeautifulSoup), data cleaning (Pandas).

2. Statistics Canada API → CPI integration.

3. Power BI → Visualization & storytelling dashboard.

4. GitHub → Version control and project sharing.

Key Insights:

1. Grocery basket inflation outpaces official CPI.

2. Walmart is the cheapest retailer across tracked items.

3. Protein (chicken, beef) are the biggest cost drivers.

Dashboard & Repository

Explore the Power BI dashboard and full dataset in this repo.

Note: Some prices (Metro & Loblaws) are simulated based on market positioning due to scraping restrictions.
