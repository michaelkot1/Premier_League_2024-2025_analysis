# Premier League 2024–2025 Data Analysis

## Overview
This project analyzes team and player-level data from the 2024–2025 Premier League season to identify statistical patterns that distinguish winning teams from losing teams beyond goals and goals conceded.

## Data
- Team-level statistics
- Player-level statistics aggregated by position
- Multiple CSV sources merged using a custom name-matching script to prevent null joins

## Methodology
- Cleaned and standardized datasets
- Matched inconsistent team/player naming across sources
- Created position-based aggregates
- Calculated correlations with end-of-season points
- Visualized key relationships to find patterns

## Key Findings
- Possession and progressive actions correlate more strongly with success for top teams
- Wage structure amplifies, but does not fully explain, performance
- Defensive metrics show delayed correlation effects

## Visualizations
(Embedded images)

## How to Run
```bash
pip install -r requirements.txt
