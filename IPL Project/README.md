# IPL 2024: Royal Challengers Bengaluru vs Delhi Capitals Analysis

## Project Overview
This project analyzes delivery-level data from the 2024 Indian Premier League match between Royal Challengers Bengaluru (RCB) and Delhi Capitals (DC). The analysis explores run scoring, batting contributions, wickets, and performance across different phases of the innings.

## Objectives
- Inspect and prepare the match dataset without unnecessarily deleting records.
- Analyze run distribution across overs.
- Identify the leading run contributors.
- Examine bowling and wicket-taking performance.
- Explore dismissal types and partnerships.
- Compare performance across Powerplay, Middle, and Death phases.
- Visualize cumulative runs and wickets.

## Dataset
The dataset contains delivery-level match information, including:
- Team
- Over
- Batter
- Bowler
- Non-striker
- Batter runs
- Extras
- Total runs
- Player dismissed
- Wicket type
- Fielders

The dataset contains **247 delivery records and 11 columns**. Records with empty dismissal fields were retained because these fields can be empty when no dismissal occurs.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Analysis Performed
1. Data inspection and cleaning
2. Run distribution across overs
3. Top run contributors
4. Wicket-taking and bowling analysis
5. Dismissal-type analysis
6. Partnership analysis
7. Powerplay, Middle, and Death phase analysis
8. Top batter strike-rate analysis
9. Strike-rate comparison across innings phases
10. Cumulative runs and wickets visualization

## Key Findings
- **Axar Patel (AR Patel)** was the leading run contributor in the analyzed dataset, with 56 runs.
- **Rajat Patidar (RM Patidar)** scored 51 runs.
- **Will Jacks (WG Jacks)** scored 39 runs.
- The cumulative-runs visualization showed RCB finishing with a higher total than DC in the supplied dataset.
- The phase-based analysis compared runs and wickets across the Powerplay, Middle, and Death overs.

## Project Files
The project folder contains the match dataset and analysis files used to investigate team and player performance.

## Conclusion
This project demonstrates how Python, Pandas, and Matplotlib can be used to clean, analyze, and visualize cricket match data, helping identify scoring patterns and individual contributions.

---
*Created as a data analytics portfolio project.*
