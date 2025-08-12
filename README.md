# 🏏 King Kohli Cricket Dashboard - Power BI Project

This project presents an interactive **Power BI Dashboard** that visualizes the legendary cricket journey of **Virat Kohli**, analyzing his performance across opponents, grounds, and years using real match data.

---

## 📊 Project Overview

The dashboard provides an insightful breakdown of:

- Runs scored across formats (**ODI**, **T20**, **Test**)
- Performance against different international teams
- Stadium-wise and year-wise analysis
- Match-wise milestones like **50s & 100s**

The entire dashboard is designed using a **custom cricket-themed background** to enhance visual storytelling.

---

## 🧮 Dataset Description

The dataset contains the following fields:

| Column Name | Description |
|-------------|-------------|
| `runs`      | Runs scored in each match |
| `opponent`  | Opposing team in that match |
| `ground`    | Stadium name where the match was played |
| `date`      | Date of the match |
| `match`     | Format of the match (ODI, T20, Test) |
| `match_no`  | Sequential match number |
| `total`     | Running total of runs scored |

Additional calculated columns like `IsCentury` and `IsFifty` were created using **DAX**.

---

## 🛠️ Tools Used

- **Power BI Desktop** (Data Modeling + Visualization)
- **DAX** (for calculated columns and KPIs)
- **Custom Design Background** (16:9 aspect ratio)
- **Excel/CSV** for raw data formatting

---

## 📌 Key Features

- 📅 Filter by Match Date  
- 🌍 Slice by Opponent Team  
- 🏟️ Filter by Ground  
- 🎮 Filter by Match Type  
- 📈 Year-wise performance trends  
- 💯 Visual count of 50s and 100s  
- 🧢 Career summary with KPIs like total runs, highest score, matches played  

---
## Dashboard Preview
![dashboard](https://github.com/Uday2306/ViratKohli-PowerBI-Dashboard/blob/main/dashboard)
---

## ✅ How to Use

1. Clone this repository.  
2. Open `kohli_dashboard.pbix` in Power BI Desktop.  
3. Explore and interact with the dashboard.  
4. (Optional) Replace the dataset with your own to explore other players.  

---

## 🙌 Credits

- Dashboard designed by **Uday Diwane**  
- Dataset is either custom-made or publicly sourced  
- Inspired by **India's legendary batsman — Virat Kohli**  
