**T20 World Cup Player Performance Dashboard**

** Problem Statement**
Analyze T20 World Cup player performance data.
Build a Power BI dashboard that:
Shows Runs, Wickets, Strike Rate, Economy of players.
Allows comparison between players.
Provides filters (Team, Role, Year/Span).
Helps to select a Dream Team XI based on insights.

🔹 Steps I Followed

Data Collection (Web Scraping)

Source: ESPN Cricinfo

Tool: Bright Data Web Scraper

Scraped 5 CSV files:

Best Economy

Bowling Best Figures

Highest Strike Rates

Most Runs

Most Wickets

Data Cleaning (Python + Pandas)

Removed extra spaces

Replaced "-" with NaN

Converted numeric columns to float/int

Exported cleaned CSVs

Data Transformation (Power Query in Power BI)

Refined columns

Set correct data types

Kept only relevant columns

Player Master Table (Power Query)

Combined Player columns from all datasets

Removed duplicates

Created a unified Players table

Data Modeling & DAX (Power BI)

Built relationships between Players ↔ Runs, Wickets, Economy, SR

Created DAX Measures:

Total Runs

Total Wickets

Average Strike Rate

Bowling Economy

Player Rating

Dashboard Building (Power BI)

Bar Chart → Top Batsmen (Players vs Runs)

Bar Chart → Top Bowlers (Players vs Wickets)

Scatter Plot → Runs vs Strike Rate

Scatter Plot → Wickets vs Economy

Pie Chart → Top 5 Players Contribution

Table → Player Rating Comparison

Filters / Slicers → Team, Span, Role

📊 Final Insights

Dashboard highlights consistent top performers.

Easy comparison between batsmen and bowlers.

Based on metrics, a Best XI Dream Team was selected.

Fun theme: The Best XI plays against aliens 😅.

🛠 Tech Stack

Web Scraping: Bright Data

Data Cleaning: Python (Pandas)

Data Transformation & Modeling: Power BI (Power Query + DAX)

Visualization: Power BI

📷 Dashboard Preview

👉 Add screenshot here:

![Dashboard](dashboard.png)
