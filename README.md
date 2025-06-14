# 🏅 Olympic & Migration Visualizations

## Overview

This Jupyter Notebook presents two distinct data visualizations based on **Olympic athletes** and **global migration**. It involves using Seaborn for a stacked bar chart and a modified version of an **alluvial diagram** for representing migration flows.

### 🥇 The Most Decorated Olympians of All Time  
<img alt="Screenshot 2025-02-15 at 9 22 46 PM" src="https://github.com/user-attachments/assets/8cd6b9a5-26cb-4f96-84b9-10fb69c89ecd" />

### 🌍 Immigration and Emigration Between Various Regions of the World  
<img alt="Screenshot 2025-02-15 at 9 24 58 PM" src="https://github.com/user-attachments/assets/24bf7013-e525-4f08-850e-c0ed0c92525a" />

The visualizations use **`pandas`**, **`matplotlib`**, **`seaborn`**, and a custom script (`alluvial.py`) to generate the graphics.

---

## 🔍 Objective

### 🎽 Part 1: Olympic Medal Stacked Bar Chart
- Create a stacked **bar chart of top Olympians by medal count** using:
  - **Seaborn’s `barplot()`** (in a **single line** of code)
  - Medal colors:  
    - 🥇 Gold → `#FFD700`  
    - 🥈 Silver → `#C0C0C0`  
    - 🥉 Bronze → `#B08D57`  
  - Proper axis labeling and bar ordering
  - Only Seaborn's barplot() is used for rendering — no other plot calls

---

### 🌍 Part 2: Alluvial Diagram of Migration Flows
- Generate an **alluvial (Sankey-style) diagram** using `migration.csv` and the provided `alluvial.py` script
- Represent **flows between global regions**
- Apply required region colors:
  - `#07C8E3` – North America  
  - `#00DA80` – Europe  
  - `#FFBB18` – Central/South America  
  - `#F60048` – Asia  
  - `#00305D` – Africa  
  - `#5C2483` – Oceania
- Modify the code so **wider flows appear on top** of thinner ones
- Ensure **labeling**, **layering**, and **order** of flows match the original specification

---

## 📁 Files Included

- `Assignment-4.ipynb` – Main notebook with code and visualizations  
- `olympic_athletes.csv` – Dataset containing athlete performance details  
- `migration.csv` – Dataset for visualizing international migration  
- `alluvial.py` – Modified plotting script for alluvial diagram  

---

## 📊 Visualization Preview

The notebook generates:
- A clean, color-coded **Olympic medal bar chart** sorted by athlete
- A detailed **migration flow diagram** using curved layered flows between world regions

---

## 🧪 Technologies Used

- Python  
- [pandas](https://pandas.pydata.org/)  
- [matplotlib](https://matplotlib.org/)  
- [seaborn](https://seaborn.pydata.org/)  
- Custom alluvial plotting script (`alluvial.py`) from [vinsburg/alluvial_diagram](https://github.com/vinsburg/alluvial_diagram)

---

## 📚 References

- Olympic dataset
- Migration data
- Alluvial code base: [https://github.com/vinsburg/alluvial_diagram](https://github.com/vinsburg/alluvial_diagram)

---

## ✍️ Attribution

All preprocessing, code structure, and visualization logic are my own unless otherwise noted.  
External resources were used for reference but not copied directly.  
Custom code edits to `alluvial.py` are integrated into the notebook.
