# UCLA WBB vs. USC (2025 Season) - Analytics Deep Dive

### Project by Abby Seseri

---

## Objective

This project analyzes the play-by-play data from the three matchups between UCLA and USC during the 2025 season. The goal is to move beyond the box score to uncover deeper, actionable insights into player and lineup effectiveness to support coaching staff strategy.

---

## Key Findings

This analysis produced two primary insights:

### 1. Individual Player Impact

The analysis confirms the on-court plus-minus for each player across the series, identifying the individuals with the most significant impact on the team's point differential.

![Individual Plus-Minus Chart](ucla_wbb_plus_minus_final.png)

### 2. A Highly Potent Lineup Combination

By normalizing lineup data to **Plus-Minus per 5 Minutes**, we can identify the most *efficient* five-player units. The data reveals that the lineup of **Elina Aarnisalo, Janiah Barker, Kiki Rice, Lauren Betts, and Timea Gardiner** was UCLA's most effective combination on a per-minute basis, suggesting an elite level of efficiency and chemistry.

![Lineup Effectiveness Chart](ucla_wbb_lineup_analysis.png)

---

## How to Run This Analysis

1.  Clone this repository.
2.  Ensure you have `pandas`, `matplotlib`, and `seaborn` installed.
3.  Open and run the Jupyter Notebook: `ucla_wbb_analysis.ipynb` (or whatever you name it). The notebook will process the included `2025USCvsUCLA.csv` file and regenerate the graphics.
