# 🏏 IPL Player Performance Analysis (2008 - 2024)

> An interactive Exploratory Data Analysis (EDA) of IPL data using **Pandas**, **Plotly**, and **Seaborn** in **Jupyter Notebook**.

---

## ✨ Overview

This project provides a comprehensive analysis of the **Indian Premier League (IPL)** matches and player statistics from **2008 to 2024**, with a special focus on player performance, team stats, venues, and memorable rivalries.

Using two primary datasets: `matches.csv` and `deliveries.csv`, we've built dynamic visualizations to reveal deep insights into:

* 🏋️ Batsmen and Bowlers performance
* 🏢 Venue and city dynamics
* ⚔️ Head-to-head player rivalries
* 📊 Seasonal & team-based trends

All visualizations are powered by **Plotly** for interactivity and better storytelling.

---

## 📃 Dataset Description

### 1. `matches.csv`

Contains match-level information:

| Column Name       | Description                           |
| ----------------- | ------------------------------------- |
| `id`              | Unique match identifier               |
| `season`          | Year of the IPL season                |
| `date`            | Date of the match                     |
| `city`            | City where match was played           |
| `venue`           | Specific stadium of the match         |
| `team1`, `team2`  | Competing teams                       |
| `toss_winner`     | Team that won the toss                |
| `toss_decision`   | Decision taken after winning the toss |
| `winner`          | Team that won the match               |
| `player_of_match` | Best performing player                |
| `umpire1/2/3`     | Umpires officiating the match         |

### 2. `deliveries.csv`

Contains ball-by-ball delivery data:

| Column Name        | Description                              |
| ------------------ | ---------------------------------------- |
| `match_id`         | Reference to `matches.csv`               |
| `inning`           | 1st or 2nd innings                       |
| `batting_team`     | Team batting during delivery             |
| `bowling_team`     | Team bowling during delivery             |
| `over`, `ball`     | Over and ball number                     |
| `batter`, `bowler` | Batsman and bowler involved              |
| `batsman_runs`     | Runs scored off the bat                  |
| `extra_runs`       | Extras: no-ball, wide, etc.              |
| `total_runs`       | Sum of batsman + extras                  |
| `player_dismissed` | Name of player dismissed (if any)        |
| `dismissal_kind`   | Type of dismissal (e.g., bowled, caught) |

---

## 🌐 Interactive Visualizations

### ✅ 1. Data Cleaning & Preparation

* Removed duplicates and missing values
* Standardized column names
* Converted dates to `datetime`

### 🏆 2. Batsman Analysis

* **Top 10 run scorers** (overall)
* **Top batsmen by team** (with dropdown selector)
* **Top batsmen by season**(with dropdown selector for season)
* **Top batsmen by season & team** (team-season selector)
* **Top batsmen by venue**

### 🌿 3. Bowler Analysis

* **Top 10 wicket takers** (overall)
* **Top bowlers by team** (dropdown)
* **Top bowler by season**(with dropdown selector for season)
* **Top bowlers by season & team**
* **Top bowlers by venue**

### 🏠 4. Venue and City Analysis

* **Top cities** with most matches hosted
* **Matches played by teams** per selected city

### ⚔️ 5. Player Rivalries

* **Top 10 Batsman vs Bowler rivalries**
* Stats include: runs, balls faced, dismissals, boundaries, innings faced

---

## 📅 Technologies Used

* **Python** (v3.10+)
* **Pandas** & **NumPy** for data manipulation
* **Plotly** for interactive charts
* **Matplotlib** & **Seaborn** for static visualizations
* **Jupyter Notebook** for presentation

---

## 📖 How to Run

```bash
# Clone the repo
https://github.com/<your-username>/ipl-eda-analysis.git

# Open Jupyter Notebook
jupyter notebook

# Run the notebook: IPL_Player_Performance_Analysis.ipynb
```

---

## 🚀 Future Improvements

* Add **player consistency ratings**
* Predictive modeling (e.g., player performance forecast)
* Web dashboard using Streamlit or Dash

---

## 🙏 Acknowledgments

* [Kaggle IPL Dataset (2008-2020)](https://www.kaggle.com/datasets/moumita09/ipl-complete-dataset-2008-2020)
* Plotly documentation for interactive dropdowns

---

## 🚀 Project Author

Made with passion by **Prerak Nagpal**
[LinkedIn](https://www.linkedin.com/in/prerak-nagpal-1815ba24a/) | [GitHub](https://github.com/prerak20code) | [LeetCode](https://leetcode.com/u/prerak1234/) colab link for the notebook:https://github.com/prerak20code/IPL-Data-analsysis/tree/main

---

> ✨ Hope you enjoy exploring the IPL as much as we enjoyed building this EDA!
