## Runningbacks 'The Age Cliff' Study

## Overview
This project explores the decline in production among superstar NFL running backs as they age — commonly referred to as the "age cliff." Using 25 seasons of NFL player and fantasy data, the analysis identifies when top-performing running backs tend to peak and how quickly their fantasy production declines afterward.

## Tools Used
- Python (pandas, matplotlib, nfl_data_py)
- Jupyter Notebook

## Methodology
1. Pulled player statistics and metadata from 1999–2023 using `nfl_data_py`
2. Filtered for running backs with **three or more 1,000+ yard seasons** to identify true high-usage backs
3. Calculated each player’s age during each season using birth year
4. Engineered performance metrics: PPR points/game, total touches, yards, and touchdowns
5. Grouped data by player and age to compare production trajectories

## Visualization
- Created line plots showing each player’s fantasy points per game vs. age
- Color-coded by player for easy comparison
- Organized into small grouped charts for visual clarity

## Key Insights
- Most superstar RBs peak between **ages 24–27**
- Production tends to **drop sharply after age 28**, particularly in PPR formats
- Some outliers (e.g., Frank Gore) maintain stable output into their 30s, but most experience a steep decline
- The age cliff is real and has strong implications for both NFL front offices and fantasy football managers

## Files Included
- `runningbacks.ipynb` – Full analysis with code, visualizations, and age-based performance trends
