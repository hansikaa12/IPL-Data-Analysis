# 🏏 IPL Data Analysis – Exploratory Data Insights from Indian Premier League

## 📌 Problem Statement

The Indian Premier League (IPL) is one of the most popular cricket leagues in the world. With every season generating massive amounts of data, analyzing past matches and player performance can offer deep insights into team strategies, player efficiency, and winning patterns.

This project aims to perform Exploratory Data Analysis (EDA) on IPL match and delivery data to uncover meaningful trends and visual patterns.

---

## 🎯 Objectives

- Load and clean IPL match and ball-by-ball delivery datasets.
- Perform comprehensive EDA on player and team performance.
- Derive business questions for both **batting** and **bowling** perspectives.
- Visualize match outcomes, toss decisions, run rates, top performers, and venue trends.
- Use the insights to answer practical questions relevant to team management and cricket analytics.

---

## 🧠 Aim

To extract meaningful insights from IPL datasets that can assist stakeholders (team analysts, coaches, fans) in understanding game dynamics and making data-driven decisions.

---

## 📚 Dataset Description

Two datasets were used:

### 1. `matches.csv`
- Match ID, season, date
- Teams, toss result, venue
- Match winner, result margin
- Player of the Match, umpire info

### 2. `deliveries.csv`
- Ball-by-ball data for each match
- Batsman, bowler, runs scored
- Wickets, extras, over number
- Match ID (foreign key)

---

## 📊 Exploratory Data Analysis (EDA)

Key analyses performed:

- Total matches played per season
- Most successful teams and venues
- Toss decision impact on match result
- Player of the Match frequency
- Top run scorers and wicket takers
- Strike rate vs economy rate analysis
- Team-wise win distributions
- Runs per over trends and partnerships

---

## 📈 Visualizations

- Bar plots, pie charts, and histograms
- Line charts for season-wise trends
- Heatmaps for team performance
- Violin and box plots for runs/wickets
- Custom interactive visuals (optional via Plotly or Power BI)

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Plotly (optional)
- Power BI (for dashboard and stakeholder-ready visuals)

---

## 🏆 Key Insights

- Batting first vs chasing trends differ by venue and season
- Certain players dominate specific teams (e.g., top scorers vs top bowlers)
- Toss winners win ~51–55% of matches (marginal edge)
- Some stadiums favor high scoring (e.g., Wankhede) while others support bowling (e.g., Chepauk)

---

## 💼 Business Use Cases

1. **Batting Strategy**:
   - Which players perform best at specific venues?
   - What is the optimal powerplay run rate?

2. **Bowling Strategy**:
   - Which bowlers contain runs during death overs?
   - Which team concedes the least extras?

---
