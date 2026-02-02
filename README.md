# 🏏 Cricket Match Simulation & Post‑Match Analysis (Python)

This repository contains a **cricket batting‑innings simulation** and a **post‑match analytical notebook** built using Python. The project focuses on **reconstructing ball‑by‑ball data** for a batting side and extracting meaningful match insights through data analysis and visualisation.

> ⚠️ This is **not a full cricket engine**. The scope is intentionally limited and clearly defined.

---

## 📌 Project Overview

The project is split into **two Jupyter notebooks**:

1. **Data Collection / Simulation Notebook**
   Simulates a single innings for the *batting side only* and generates ball‑by‑ball match data.

2. **Post‑Match Analysis Notebook**
   Uses the generated data to analyse scoring patterns, player impact, partnerships, run rates, and match momentum.

The primary goal is **analysis**, not automation or real‑time ingestion.

---

## 🎯 Objectives

* Translate real cricket rules into programmatic logic
* Generate structured ball‑by‑ball data
* Perform meaningful **post‑match analysis**
* Visualise match flow and player contributions
* Demonstrate domain‑driven analytical thinking

---

## 🧠 Simulation Notebook – Key Features

* Batting‑side innings simulation
* Ball‑by‑ball state tracking:

  * Runs
  * Wickets
  * Overs & balls
  * Extras (wide, no‑ball, etc.)
* Handles common cricket scenarios:

  * Legal & illegal deliveries
  * Extras without legal ball count
  * Cumulative score & wickets
* Outputs **analysis‑ready tabular data**

### Known Limitations (By Design)

* Bowling side not modelled
* Some run permutations couldn't be included because of time limitations
* Built within a **3‑day time constraint**

---

## 📊 Post‑Match Analysis Notebook – Key Insights

* Score & wicket progression over time
* Run rate trends
* Player‑wise run contribution
* Strike rate vs consistency analysis
* Partnership analysis based on wicket falls
* Extras impact on total score
* Visual storytelling using matplotlib & seaborn

The notebook focuses on **explaining what happened in the match**, not just computing statistics.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📈 Skill Demonstrated

* Domain‑driven feature engineering
* Stateful simulation logic
* Data cleaning & transformation
* Exploratory data analysis (EDA)
* Sports analytics thinking
* Visual interpretation of match flow

---


## 🚀 Future Improvements (Optional)

There is scope for further improvementss in this model which can include:

* Bowling‑side modelling
* Expand run‑type coverage and more.

---

## 📬 Feedback

Suggestions, critiques, and improvements are welcome. The project is intentionally open for iteration and learning.

---

⭐ If you find this interesting, feel free to star the repository!
