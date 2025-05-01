# 🎯 PDC World Darts Championship Analytics  
**Interactive Power BI Dashboard + Web Scraper**

## 📌 Project Overview  
This project combines a Python-based web scraper with a dynamic Power BI dashboard to analyze player performance in the 2025 PDC World Darts Championship. The solution extracts detailed match stats from Flashscore and visualizes them at the player level to uncover trends and performance insights.

## 🛠 Key Features  

- **Automated Data Collection**  
  Scrapes match results and performance metrics such as averages, checkouts, and high scores from Flashscore.

- **Player-Level Granularity**  
  Structures stats so each player has their own record for every match, enabling detailed individual analysis.

- **Power BI Visualization**  
  Interactive dashboards visualize key statistics such as:
  - 3-dart averages
  - Checkout efficiency
  - High scoring throws (100+, 140+, 180s)
  - Highest checkouts
  - Tournament stage comparisons

- **End-to-End Pipeline**  
  Includes scraping, data cleaning, transformation, and visualization — providing a full data analytics workflow from raw HTML to insight.


## 🔧 Tech Stack  
- **Python**: Selenium, BeautifulSoup, pandas  
- **Power BI**: Data modeling, custom visuals, slicers  
- **DAX**: Measures for dynamic averages, filters, and comparisons  
- **Excel Export**: For flexible data handling and integration with Power BI  

## 🚀 Future Enhancements  
- Add historical year-on-year comparisons  
- Integrate player bios and rankings  
- Visualize progression through the bracket  
- Add predictive performance indicators (e.g., expected checkout success)
