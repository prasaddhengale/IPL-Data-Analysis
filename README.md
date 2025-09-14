# 🏏 IPL Data Analysis (2008–2020)

## 📌 Project Overview
This project analyzes **193,000+ IPL ball-by-ball records** from 2008 to 2020 to uncover patterns in batting, bowling, and team performance.  
The analysis includes player stats, boundary counts, dismissal types, and over-wise scoring trends to provide insights into the evolution of IPL cricket.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 📂 Dataset
- **File:** `IPL Ball-by-Ball.csv`  
- **Rows:** 193,468  
- **Columns:** Match ID, Over, Ball, Batsman, Bowler, Runs, Wickets, Dismissal Type, Batting Team, Bowling Team, etc.
- **Source:** [IPL Dataset (2008 - 2020)](https://www.kaggle.com/datasets/hiimanshuagarwal/ipl-dataset-2008-2020)

---

## 📊 Analysis & Visualizations

### 🔹 1. Data Cleaning
- Removed missing values (e.g., `bowling_team`).
- Dropped duplicates to ensure accurate stats.

### 🔹 2. Runs Distribution (Batsmen Performance)
- Identified **Top 10 run-scorers** in IPL history.
- Visualized their total runs in descending order.

### 🔹 3. Boundary Analysis (4s & 6s)
- Counted and plotted most prolific boundary hitters.
- Compared total number of 4s vs 6s for top players.

### 🔹 4. Bowling Analysis
- Ranked top wicket-takers.
- Created bar plots to highlight leading bowlers.

### 🔹 5. Team Performance (Runs Scored)
- Calculated total runs scored by each IPL team across all seasons.
- Compared team performances visually.

### 🔹 6. Dismissal Types
- Created a **pie chart** to show the distribution of dismissal types (caught, bowled, run out, etc.).

### 🔹 7. Over-Wise Run Rate
- Analyzed average runs scored per over (1–20).
- Identified Powerplay, middle overs, and death overs scoring trends.

---

## 📷 Sample Visuals
<img width="915" height="545" alt="download" src="https://github.com/user-attachments/assets/43798cd6-fe3b-47e1-b8e9-ca713d28e802" />
<img width="1024" height="545" alt="download" src="https://github.com/user-attachments/assets/6c6b70f4-d3dd-46c9-b4bf-4e3ce982ade7" />
<img width="846" height="545" alt="download" src="https://github.com/user-attachments/assets/70558820-5b4a-4c46-985e-7721dacfd42d" />


---

## 📌 Key Insights
- **Virat Kohli** leads IPL run-scoring charts, followed by **Suresh Raina** and **David Warner**.
- Players like **Chris Gayle** and **AB de Villiers** dominate despite fewer balls faced — showcasing explosiveness.
- **Lasith Malinga** tops the wicket charts, proving his impact in death overs.
- Teams like **Mumbai Indians** and **Royal Challengers Bangalore** consistently score big.
- **Overs 19 & 20** contribute the most runs, reflecting aggressive death-over batting.

---

## 🚀 How to Run
- Download the notebook and dataset from this repo.
- Open the notebook in Jupyter and run all cells to reproduce the analysis.

