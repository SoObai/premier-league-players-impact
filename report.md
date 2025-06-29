# Premier League Players Impact – Project Report

- Obai Ali 

---

## 🧠 Project Summary

This project explores football performance data to build an interactive visualization dashboard. The application offers six types of charts to interpret various metrics such as goals, penalties, and disciplinary actions using D3.js.

---

## 📦 Dataset

Originally proposed using World Bank data, the project evolved to use a football dataset focusing on Premier League players. Each row in the dataset includes:

- Player Name
- Team
- Position
- Goals
- Penalties
- Yellow Cards
- Red Cards

The data is now located in `data.csv` in the project root.

---

## 📊 Visualizations Breakdown

### 1. **Bar Chart**

- Displays each player's total goals.
- Players sorted by goal count.

### 2. **Scatter Plot**

- Plots Goals (x-axis) vs. Penalties (y-axis).
- Visualizes correlation patterns.

### 3. **Bubble Chart**

- Each bubble = one team.
- Size = total goals, color = total cards.

### 4. **Donut Chart**

- User selects a team.
- Donut shows goal distribution among players in that team.

### 5. **Stacked Bar Chart**

- Shows total goals by player position.
- Highlights position-based performance.

### 6. **Box Plot**

- Shows statistical range (min, Q1, median, Q3, max) of player goals per team.

---

## 🔁 Changes from Initial Plan

- Initially planned to build with non-sports health data.
- Shifted to football due to clearer narrative and data richness.
- Interconnected visualizations were added for a smoother user experience.
- Enhanced interactivity: tooltips, dropdowns, real-time updates.

---

## 🛠 Development Highlights

- Built entirely with **D3.js**, no frameworks or backend.
- Each chart is modular and independently functional.
- Clean and documented JavaScript.
- Designed with ease of use and performance in mind.

---

## 👥 Team Collaboration

- ~100 hours invested.
- Tasks split equally.
- Weekly coordination for debugging and review.
- Overcame challenges in rendering multidimensional and categorical data.

---

## 🔚 Conclusion

This project helped us practically apply data visualization theories and techniques in a real-world-like scenario. We successfully created a visually rich and informative dashboard that enables users to gain insight into football players' performances.

It also enhanced our teamwork, project planning, and frontend development skills using D3.js.

---
