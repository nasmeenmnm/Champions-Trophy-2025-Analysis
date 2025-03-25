📊 ICC Champions Trophy 2025 - Power BI Dashboard

📌 Project Overview
This Power BI dashboard provides an in-depth analysis of team, batting, bowling, and match performance in the ICC Champions Trophy 2025. The data has been web-scraped from Cricbuzz using BeautifulSoup, cleaned, transformed, and visualized in Power BI.

📂 Project Workflow
1️⃣ Data Collection: Web Scraped live cricket statistics from Cricbuzz using BeautifulSoup.
2️⃣ Data Cleaning & Processing: Cleaned and formatted data using Pandas, handled missing values, and stored it in CSV files.
3️⃣ Power BI Transformation: Imported data, transformed it using Power Query, and created calculated columns and measures.
4️⃣ Dashboard Design & Insights: Created interactive dashboards focusing on different performance metrics.

📊 Key Features
✅ Teams Performance - Displays total matches played, runs scored, and wickets taken.
✅ Batting Analysis - Shows total runs, strike rates, boundaries, and top batsmen stats.
✅ Bowling Insights - Highlights wickets, economy rate, bowling averages, and top bowlers.
✅ Match Performance - Tracks match results, overs bowled, and team-wise comparison.
✅ Dynamic Interactivity - Filters and slicers for easy navigation across teams, players, and matches.

📌 Power BI Measures Used
Total Runs = SUM(Batting[Runs])

Bowling Economy = DIVIDE(SUM(Bowling[Runs Conceded]), SUM(Bowling[Overs Bowled]))

Batting Average = DIVIDE(SUM(Batting[Runs]), COUNT(Batting[Dismissals]))

Wickets Taken = COUNT(Bowling[Wickets])

Strike Rate = DIVIDE(SUM(Batting[Runs]), SUM(Batting[Balls Faced])) * 100

Inactive Relationship Measures: Used USERELATIONSHIP() to extract inactive relationships in Power BI.

📷 Dashboard Screenshots
🔹 Batting & Bowling Performance Overview
🔹 Team-wise & Match-wise Analysis
🔹 Top Performers & Key Metrics
![1](https://github.com/user-attachments/assets/46da1ec7-f74c-4207-a8b0-10208b48fa35)
![2](https://github.com/user-attachments/assets/6ce58b33-2577-4cdc-9372-88f78087856f)
![3](https://github.com/user-attachments/assets/765445b4-d27d-4abd-8bc6-403f4bf1a313)
![4](https://github.com/user-attachments/assets/051ba4fa-62f2-4afa-89eb-8a0c47e0baca)


📦 Tech Stack
🔹 Pyth
on (BeautifulSoup, Pandas, Matplotlib)
🔹 Power BI (Power Query, DAX, Data Transformation)
🔹 Web Scraping (Cricbuzz Data)
🔹 CSV for Data Storage
