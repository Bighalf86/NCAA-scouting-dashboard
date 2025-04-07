# 🏀 NCAA-scouting-dashboard
_Visual dashboard for NCAA basketball player scouting. Built using Tableau; data cleaned in Excel from public sources._

## 📌 Overview

This project presents an MVP (Minimum Viable Product) of a **basketball scouting dashboard**, built using **Tableau** and based on real user insights from a semi-structured interview with a professional basketball head coach. The goal was to create a visual analytics tool that helps **analyse and explore a large player database (5,100+ records)** in an intuitive and interactive way.

The NCAA player database was created by **extracting data from publicly available sources**, including **RealGM**, **ESPN**, and **KenPom.com**. The data was then **cleaned and transformed in Excel using Power Query** to prepare it for use in Tableau.

👉 **[View the live dashboard on Tableau Public](https://public.tableau.com/app/profile/alessandro.mezzone/viz/2024NCAAScoutingProject_V2_9p_e_r/Dashboard2#1)**  

![Dashboard Preview](https://github.com/user-attachments/assets/af03ac6e-e534-4fb3-827e-bbb6354ae63b)

---

## 🎯 Key Features

- **Player Type-Based Filtering**:  
  Players are grouped by **pre-defined types** rather than traditional court positions, as requested by the HC. A dropdown menu lets users select a player type, updating the visualisation accordingly.

- **Scatter Plot-Style Visualisation**:  
  Inspired by Carroll (2020), players are displayed in a horizontal ranking format:
  - **X-axis** ranks players based on a composite KPI score.
  - **Y-axis** is "fake" – used to space out data points and avoid overlap.

- **Composite KPI Calculation**:  
  A preliminary ranking method was applied using a **coefficient**:
  - Sum of positive KPIs
  - Minus negative KPIs
  - Divided by the number of KPIs selected  
  *(To be refined with stakeholder input in future iterations)*

- **Interactive Filtering Options**:
  1. **Player Type** (dropdown menu)
  2. **Physical Attributes** (Height & Weight)
  3. **Advanced Stats** (Efficiency, True Shooting %, Points per Possession)
  4. **College Class** (Freshman, Sophomore, Junior, Senior)

- **Detailed Player Info on Click**:  
  Clicking a data point reveals **basic stats from the current season** for the selected player.

---

## 🛠️ Tools Used

- **Tableau Public** – For data visualisation and dashboard development
- **Excel (Power Query)** – For cleaning and transforming raw data
- **Public Web Sources** – RealGM, ESPN, KenPom.com

---

## 🧠 Insights

This dashboard is a first iteration designed with real stakeholder needs in mind. It focuses on:
- Using **data visualisation to simplify large datasets**
- Customising the view based on practical scouting workflows
- Integrating data from **multiple public sources**, then transforming it into a unified dataset with **5100 NCAA player records**
- Laying the foundation for further refinement and expansion in collaboration with end-users

---

## 📎 Credits & References

- Visualisation concept inspired by Carroll (2020) – Football scouting dashboards
- Data sourced from:  
  - [RealGM](https://www.realgm.com/)  
  - [ESPN](https://www.espn.com/)  
  - [KenPom](https://kenpom.com/)

---

## 🚀 Next Steps

- Refine KPI scoring method with stakeholders
- Expand dataset with additional performance metrics
- Add dynamic comparison between players or player types
