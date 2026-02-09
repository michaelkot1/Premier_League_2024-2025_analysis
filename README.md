# Premier League 2024–2025 Data Analysis

## Overview
This project analyzes team and player-level data from the 2024–2025 Premier League season to identify statistical patterns that distinguish winning teams from losing teams beyond goals for and against. 
View folder Tableau Worksheets to see Tableau Visuals that I made from the same data.

## Data
I aggregated team and positional data into five Tactical Buckets to measure performance per 90 minutes:
  - Defensive Activity: Positional touches and tackle efficiency.
  - Ball Progression: Verticality via progressive passes and carries.
  - Attacking Threat: xG, assists, and final-third presence.
  - Territory Gain: Total distance carried and ball-carrying volume.
  - Central Connectivity: Middle-third control and receiving volume.

## Methodology
- Merged multiple CSV sources using a custom name-matching script to resolve naming inconsistencies across datasets.
- Matched inconsistent team/player naming across sources
- All volume metrics were converted to Per 90 stats to ensure fair comparison regardless of games played.
- Created custom indices like the Progressive Attack Score and Points ROI to measure efficiency.

## Key Findings
- There is a high correlation between spend and points, but the "ROI" analysis identifies which mid-table clubs are the most efficient recruiters.
- High defensive involvement in the midfield often correlates with higher goals conceded, suggesting a lack of control rather than defensive stability.
- Elite teams don't just pass, they show high efficiency in both progressive passing and progressive carrying, making them multi-dimensional threats.

## Visualizations
The analysis includes 7 core visualizations:

1. The Financial Floor: Spending vs. League Points.

2. Points ROI: Efficiency per £1m spent.

3. The Midfield Trap: Midfield workload vs. Goals Conceded.

4. Back-Line Progression: Defensive verticality vs. Total Points.

5. Overall Attack Threat: Cumulative tactical output vs. League Success.

6. Progression Archetypes: Passers vs. Carriers.

7. Control vs. Penetration: Midfield possession vs. Final-third entry.

## How to Run in Terminal
```bash
1. Clone Repo:
git clone https://github.com/michaelkot1/Premier_League_2024-2025_analysis
cd Premier_League_2024-2025_analysis

2. Create Virtual Environment
* macOS / Linux
python3 -m venv venv
source venv/bin/activate

* Windows
python -m venv venv
venv\Scripts\activate

3. Install Dependencies
pip install --upgrade pip
pip install -r requirements.txt

4. Launch Jupyter Notebooks
jupyter notebook

5. Navigate to Main File
Select file: main_inspecting.ipynb

6. Open Notebook
Select Kernel: (Python [conda env:base])

7. Click run and then run all
