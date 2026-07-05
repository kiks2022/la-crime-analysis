# LA Crime Data Analysis

## Overview
This project explores a dataset of reported crimes to uncover patterns related to time of day, location, and victim demographics.

## Objectives
The analysis answers the following questions:

1. Which hour of the day has the highest frequency of crimes?
2. Which area has the largest frequency of night crimes (10:00 PM – 3:59 AM)?
3. How many crimes were committed against victims in each age group?

## Key Findings

| Question | Answer |
|---|---|
| Peak crime hour | 12 (Noon) |
| Area with most night crimes | Central |
| Victim age group with most crimes | 26-34 (47,470 crimes) |

### Victim Age Group Breakdown

| Age Group | Number of Crimes |
|---|---|
| 0-17 | 4,528 |
| 18-25 | 28,291 |
| 26-34 | 47,470 |
| 35-44 | 42,157 |
| 45-54 | 28,353 |
| 55-64 | 20,169 |
| 65+ | 14,747 |

### Observations
- Crime reports peak around **noon**, though this may partly reflect how missing or unknown times get logged in the source data.
- **Central** area sees the highest concentration of night-time crimes (10pm–3:59am).
- Victims aged **26-34** and **35-44** account for the largest share of crimes, consistent with working-age adults being more exposed to crime through commuting, work, and general activity levels. Both younger (0-17) and older (65+) groups show noticeably lower counts.

## Tools Used
- Python
- pandas
- numpy
- Jupyter Notebook

## Files
- `notebook.ipynb` — Full analysis code, with outputs included
- `README.md` — Project summary (this file)
- `data/crimes.csv` — Source dataset

## How to Run
1. Clone this repository
2. Install dependencies: `pip install pandas numpy`
3. Open `notebook.ipynb` in Jupyter Notebook or JupyterLab
4. Run all cells to reproduce the analysis

## Data Source
Dataset provided via [DataCamp](https://www.datacamp.com/) as part of a guided project.

> **Note:** The `crimes.csv` dataset is not included in this repository due to its file size. To run the notebook yourself, download the dataset from the original DataCamp project and place it in a `data/` folder in the project root.
