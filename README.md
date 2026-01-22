# WC23 Cricket Analysis 🏏

## 📌 Project Overview
This project analyzes **ICC Cricket World Cup 2023** data to understand  
team performance, player contributions, batting order impact, and ground-wise trends  
using **Python-based data analysis and visualization**.

The goal is to extract **meaningful insights** from match, batting, and bowling data
rather than building prediction models.

---

## 📂 Datasets Used
The analysis is based on the following datasets:

- `Cricket_WC23.csv` – Match results and outcomes
- `BATTING.csv` – Player batting statistics
- `BOWLING.csv` – Player bowling statistics
- `PLAYERS_INFO.csv` – Player and team information

---

## 🧠 Key Analysis Performed

### 🏏 Team & Match Analysis
- Batting first vs batting second win comparison
- Ground-wise match outcome analysis
- Ground bias based on batting order
- Most successful teams at each ground

### 🧑‍🏏 Batting Analysis
- Top run scorers
- Runs per match (consistency)
- Strike rate vs runs analysis
- Team-wise batting performance
- Top Indian batsmen based on custom batting rating

### 🎯 Bowling Analysis
- Top wicket takers
- Wickets vs matches comparison
- Economy and discipline metrics
- Top Indian bowlers based on personal bowling rating

---

## 📊 Visualizations
- Bar charts (rankings & comparisons)
- Stacked bar charts (ground bias)
- Dot plots (runs vs strike rate)
- Donut chart (batting order wins)

All visualizations are placed **directly below their respective analysis**
for better readability and storytelling.

---

## 🛠 Tools & Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📌 Key Insights
- Batting order impact varies by ground conditions
- Some grounds strongly favor chasing teams
- Consistency metrics reveal impact beyond total runs
- Indian bowlers showed strong discipline and effectiveness

---

## 📁 Project Structure
wc23-cricket-analysis/
├── BATTING.csv
├── BOWLING.csv
├── Cricket_WC23.csv
├── Team_analysis.ipynb
├── WC_Batting_Analysis.ipynb
└── WC_Bowling_Analysis.ipynb
