# 🏏 IPL Data Analysis (2008–2025)

Python Jupyter Notebook Data Analytics IPL Cricket

A complete end-to-end data analytics project on Indian Premier League (IPL) cricket data covering 18 seasons (2008–2025), 1,169 matches, and 278,205 ball-by-ball deliveries.

## 📋 Project Overview

This project performs a full data analytics workflow:
- **Data Loading** — 4 datasets loaded and verified
- **Exploratory Data Analysis** — shape, dtypes, null checks, duplicates
- **Data Cleaning** — null handling, dtype fixing, category conversion
- **Data Analysis** — 20+ groupby analyses across batting, bowling, teams and seasons
- **Visualization** — 50+ charts using both Matplotlib and Seaborn
- **Insights** — written insight after every chart
- **Conclusion** — full findings summary

## 📁 Dataset Information

| File | Rows | Columns | Description |
|------|------|---------|-------------|
| ball_by_ball_data.csv | 2,78,205 | 30 | Every ball bowled in IPL history |
| ipl_matches_data.csv | 1,169 | 24 | Match-level information |
| players-data-updated.csv | 772 | 8 | Player profiles and styles |
| teams_data.csv | 16 | 4 | IPL team information |

## 🛠 Libraries Used

| Library | Purpose |
|---------|---------|
| Pandas | Data loading, cleaning, groupby analysis, merging |
| NumPy | Numerical operations and array handling |
| Matplotlib | Basic charts — bar, line, pie, histogram |
| Seaborn | Statistical charts with colour themes |

## 📊 Analysis Sections

### 🏏 Batting Analysis
- Top 10 all-time run scorers
- Top 10 six hitters and four hitters
- Most balls faced
- Season-wise sixes and fours trend

### 🎯 Bowling Analysis
- Top 10 wicket takers
- Most dot balls, wide balls, extras
- Most runs conceded
- Most overs bowled

### 🏆 Team Analysis
- Total matches played, wins, losses
- Wins vs losses comparison
- Total runs by team
- Toss wins by team

### 📅 Season Analysis
- Total runs per season (2008–2025)
- Matches per season
- Season-wise boundary trends
- Average run rate per season
- Over-by-over run analysis (0–19)

### ⚡ Match Analysis
- Toss decision split (bat vs field)
- Wicket types distribution
- Match result types
- Player of the Match winners
- Innings score distribution

## 🔑 Key Findings

- **V Kohli** is the all-time IPL run scorer (8671 runs) — leads in both runs and fours
- **CH Gayle** leads six-hitting (359 sixes) — 56 more than second place
- **YS Chahal** leads wickets — spinners dominate IPL dismissals
- **Mumbai Indians** leads in wins (151), matches (277), runs (45,088) and toss wins
- Six-hitting trending strongly upward — T20 batting is getting more aggressive every season
- **Over 17–18** are the highest-scoring overs — death bowling is the hardest T20 skill
- **58.4%** of toss winners choose to field first
- **AB de Villiers** leads Player of the Match awards (25)

## 🚀 How to Run

1. Clone the repository
git clone https://github.com/yourusername/ipl-analysis.git
2. Install required libraries
pip install pandas numpy matplotlib seaborn jupyter
3. Place all 4 CSV files in the same folder as the notebook
4. Open Jupyter Notebook
jupyter notebook IPL.ipynb
5. Run All Cells → Kernel → Restart & Run All

## 📂 Repository Structure

ipl-analysis/
├── IPL.ipynb ← Main notebook
├── README.md ← This file
├── ball_by_ball_data.csv ← Ball by ball data
├── ipl_matches_data.csv ← Matches data
├── players-data-updated.csv ← Players data
└── teams_data.csv ← Teams data
