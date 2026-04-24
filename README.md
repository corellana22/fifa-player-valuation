# FIFA Player Valuation

A sports analytics project that models and analyzes player market value using FIFA player data. This project explores how performance attributes, age, and potential influence player valuation.

---

## Overview
This project uses an 18,000-player FIFA dataset to investigate the key drivers of player market value. By combining data cleaning, exploratory analysis, and regression modeling, the goal was to better understand how different attributes contribute to valuation in a sports analytics context.

---

## My Contributions
- Cleaned and prepared a large FIFA player dataset for analysis
- Explored relationships between player attributes, age, potential, and value
- Built regression models to estimate player market value
- Analyzed feature importance to identify key valuation drivers
- Created visualizations to communicate trends in player performance and value

---

## Key Findings
- Overall rating is one of the strongest predictors of player value
- Player potential significantly influences valuation, especially for younger players
- Age has a nonlinear relationship with value (younger players with high potential are more valuable)
- Position-specific attributes impact valuation differently across roles

---

## Tech Stack
- Python
- Pandas
- NumPy
- Regression modeling
- Data visualization (Matplotlib / Seaborn)

---

## Sample Insights
- Higher overall ratings strongly correlate with increased market value
- Younger players with high potential are disproportionately valued
- Certain positions (e.g., forwards) tend to have higher market value distributions

## Repository Structure
```text
fifa-player-valuation/
│
├── data/
│   └── fifa_players.csv
│
├── notebooks/
│   └── fifa_player_valuation.ipynb
│
└── README.md
