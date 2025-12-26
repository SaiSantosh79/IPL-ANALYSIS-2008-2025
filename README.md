# 🏏 IPL Analysis Dashboard – Power BI Project

## 📌 Project Overview
The Indian Premier League (IPL) generates massive volumes of match and ball-by-ball data each season.  
Analyzing this data manually makes it difficult to identify **team performance trends**, **player dominance**, and **season-wise outcomes**.

This Power BI project converts raw IPL data into an **interactive, insight-driven dashboard** that helps stakeholders understand:
- Team performance and points table
- Match outcomes (wins, losses, ties, no-results)
- Top batters and bowlers (Orange Cap & Purple Cap)
- Boundary-hitting patterns and player impact

---

## 🎯 Problem Statement
Teams, analysts, and cricket enthusiasts need a **centralized analytical view** to:
- Track team performance across seasons
- Identify top-performing batters and bowlers
- Accurately calculate points tables
- Understand match outcomes and trends

The goal of this project is to **build a dynamic Power BI dashboard** that provides **actionable insights** using IPL match and ball-by-ball data.

---

## 🛠️ Tools & Technologies
- **Power BI**
- **DAX (Advanced Measures)**
- **Power Query**
- **Data Modeling & Relationships**
- **Sports Analytics Logic**

---

## 📊 Key Dashboard Features

### 🏏 Team Performance Analysis
- Matches Played, Won, Lost, Tied, and No Result
- Dynamic **Points Table** (2 points per win, 1 per tie/no-result)
- Win Percentage for fair comparison across teams
- Season-wise filtering using slicers

---

### 🔥 Batting Insights
- **Orange Cap Holder** (most runs per season)
- Top boundary hitters (most fours & sixes)
- Player-wise run contributions
- Identification of aggressive vs consistent batters

---

### 🎯 Bowling Insights
- **Purple Cap Holder** (most valid wickets per season)
- Exclusion of non-bowler dismissals (run-outs, retired hurt, etc.)
- Bowler dominance trends across seasons

---

### 🖼️ Advanced Visual Enhancements
- Dynamic **player images** for Orange Cap, Purple Cap, and top boundary hitters
- Interactive slicers for season and team selection
- Clean KPI cards for quick decision-making

---

## 📈 Key Insights Derived

- Matches played must be calculated using **both team1 and team2 columns**, requiring `USERELATIONSHIP()` in Power BI.
- Winning teams consistently have strong **bowling units**, not just top batters.
- High boundary hitters are not always the highest run scorers, showing different batting strategies.
- Accurate points tables require proper handling of **ties and no-result matches**.
- Dynamic images significantly improve dashboard storytelling and engagement.

---

## 🧠 Business Impact
This dashboard enables:
- Faster performance comparison across seasons
- Data-driven team evaluation
- Clear identification of match-winning players
- Accurate standings and rankings without manual effort

---

## 📂 Project Structure


---

## 🔗 Author
**Santosh Manda**  
📧 Email: sathyasai79013@gmail.com  
🔗 GitHub: https://github.com/SaiSantosh79  
🔗 LinkedIn: https://www.linkedin.com/

---
