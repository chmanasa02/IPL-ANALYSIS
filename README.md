# 🏏 IPL Analysis Dashboard – Tableau Project
This repository contains an interactive Tableau dashboard analyzing historical Indian Premier League (IPL) data. It provides in-depth insights into team performance, player statistics, toss decisions, and batting/bowling metrics across multiple seasons. The dashboard is designed to assist fans, analysts, and strategists in understanding key trends and patterns in IPL history.
*** 
📌 Project Overview
---
🎯 Goal of the Dashboard :

To provide a comprehensive visual analysis of IPL statistics — including batting and bowling performance, match results, and team strategies — that supports fan engagement, performance evaluation, and decision-making for analysts, coaches, and cricket enthusiasts.

✅ Specific Objectives
- Analyze season-wise IPL winners to identify consistent top-performing teams.
- Track Orange Cap (Top Run Scorers) and Purple Cap (Top Wicket Takers) across seasons.
- Evaluate batting trends through total 4’s and 6’s hit during the tournament.
- Understand impact of toss decisions (bat vs field) on match outcomes and winning percentages.
- Visualize team-wise match wins based on toss choices and strategy execution.
- Present detailed batting metrics (runs, strike rate, 50s, 100s, boundaries) of leading players.
- Present bowling statistics (economy, average, strike rate, total wickets) of top bowlers.
- Allow users to filter by season or team to derive customized insights.
***
## ⚙️ Tools & Technologies 
- Tableau Public – For building and publishing dashboards
- Microsoft Excel / CSV – For cleaning and preparing raw IPL data
- Data Source: IPL match and player performance records
***
## 🧾Dataset Overview 
- source: Kaggle (https://www.kaggle.com/code/pranjalverma08/detailed-analysis-of-ipl-data-2008-2020/data)
1. <code>IPL Matches 2008–2020.csv</code>
- Contains high-level match information for all IPL games from 2008 to 2020.
- Key Fields: id, season, date, team1, team2, winner, venue, toss_winner, toss_decision, result, player_of_match, umpire1, umpire2
- Use Case:
Used to derive season-wise winners, toss decision analysis, team performance trends, and award stats (e.g., Player of the Match).
2. <code>IPL Ball-by-Ball 2008–2020.csv</code>
- Contains detailed ball-by-ball delivery records for every match from 2008 to 2020.
- Key Fields:match_id, over, ball, batsman, non_striker, bowler, batsman_runs, extra_runs, total_runs, dismissal_kind, player_dismissed, fielder
- Use Case:
Enables deep insights into player-level performance, strike rate, economy rate, boundaries (4s/6s), wickets taken, and over-wise scoring patterns.
***
## 🚀 Key Features of the Dashboard
- 🏆 Title Winners by Season
- 🧢 Orange Cap & Purple Cap Leaders (Top Run Scorer & Wicket Taker)
- 🎯 Team-wise Wins Based on Toss Decision
- 🥇 Toss Decision Winning % – Bat vs Field
- 💥 Total 4’s and 6’s Hit Throughout Tournament
- 👨‍🏏 Top Batsman Stats: Runs, Strike Rate, 4s, 6s, 50s, 100s
- 🎯 Bowling Insights: Economy, Average, Strike Rate, Wickets
***
## 📁 File Contents
File Name	Description
- <code>IPL ANALYSIS.twb</code> - Tableau packaged workbook with full visualizations
- <code>IPL Ball-by-Ball 2008-2020.csv</code> & <code>IPL Matches 2008-2020.csv</code> - Cleaned dataset used for Tableau analysis
***
## 🚀Getting Started
Clone the repository : 
> git clone https://github.com/yourusername/IPL-ANALYSIS.git

## Demo Of Project
OVERVIEW - 

![IPL ANALYSIS DASHBOARD -1](https://github.com/user-attachments/assets/c90d8a60-b7a7-481a-aa94-eb71b248546c)

PLAYER STATS -

![IPL ANALYSIS DASHBOARD - 2](https://github.com/user-attachments/assets/240fd1dd-1bb3-4e37-b6af-4a56b6cadecd)

