# 🏏  T20_Cricket_Data_analysis-using-web-scraping-Python-and-BI
This project focuses on analyzing T20 cricket match data using Web Scraping, Python, and Business Intelligence (BI) tools. The goal is to extract meaningful insights from real-world match data by scraping, processing, and visualizing it in an interactive and informative way.A complete data pipeline and visualization project designed to analyze T20 cricket player and match performance. This project extracts structured data directly from ESPN Cricinfo using Bright Data’s Web Scraper, cleans it using Python, and presents rich insights in a Power BI dashboard.

# 📌 Project Objectives
✅ Fully automated web scraping using Bright Data’s Data Collector
🧹 In-depth data transformation with Python & Pandas
📈 End-to-end BI pipeline in Power BI with DAX Measures, filters, and parameters
🔍 Covers individual player analysis, team stats, win patterns, toss insights, venue data & more!

# 🧰 Technologies & Tools Used
Python 🐍

requests, BeautifulSoup for web scraping

pandas, numpy, matplotlib, seaborn for data manipulation & visualization

Power BI / Tableau 📊 (for final dashboards and reporting)

Jupyter Notebook (for development & EDA)

# Web Sources:

ESPNcricinfo

Cricbuzz

ICC official website (depending on access)

# 🧭 Step-by-Step Workflow
🔹 1. Web Scraping with Bright Data
  📥 We used Bright Data’s Data Collector to scrape structured data from ESPN Cricinfo:

  Player profiles (batting, bowling, career stats)

   Match scorecards

   Team and venue summaries

📌 Steps:

Create a Bright Data account and choose “Web Scraper – Data Collector”

Target https://www.espncricinfo.com/ as the source

Configure collectors for:

Player stats

Match results

Season summaries

Export structured data as .csv or .json

Store output in the /data/raw/ directory

🔹 2. Data Cleaning & Transformation (Python 🐍)
Using Pandas for data wrangling and preprocessing:

📌 Steps:

Open notebooks/cleaning.ipynb

Remove missing/null values

Standardize date formats and player names

Engineer new features:

Win Margin Type

Strike Rate

Bowling Economy.

🔹 3. Power BI: From Data to Dashboard ⚡
🧪 Power Query Editor
Load cleaned_data.csv into Power BI

Further transform columns (e.g., split columns, change data types)

Apply filters for null handling and column renaming

🧠 Data Modeling
Define relationships between tables: Players, Matches, Teams

Create calendar table for date-based analysis

🔹 4. Dashboard Design ✨
Design visually rich dashboards with:

🎯 Player Performance Cards (Runs, SR, Avg, Wickets)

📊 Team Comparison Charts

🧩 Toss vs Win Sankey / Donut

🗺️ Venue Heatmap (Win% by location)

📆 Year-on-Year progress graphs

🧮 Interactive filters: Team, Player, Year, Venue

🧠 Future Enhancements
🧮 Integrate predictive models (match prediction, player performance)

🔄 Schedule scraping jobs via CRON or Airflow

🌐 Convert dashboard into web app using Streamlit
