# Election Analysis: Runoff Voter Turnout

This repository contains data analysis for election turnout, specifically focusing on early and mail-in voting for a runoff election, compared against registered voter rolls and first-round (May) participation.

## Overview
This project processes and standardizes disparate election data sources to calculate turnout rates at the precinct level.

### Key Analysis Features
- **Data Standardization:** Cleaning and merging data from multiple sources (Northgate early voting, Southfield early voting, and overall mail-in ballots) into a unified voter dataset.
- **Voter Matching:** Matching early voters with registered voter rolls to determine precinct-level turnout.
- **Turnout Statistics:** Calculating turnout percentages per precinct, including summary statistics (mean, median, standard deviation) for the overall dataset.
- **May Participation Tracking:** Analyzing the overlap between voters who participated in the May first-round election and those voting in the runoff.

## Data Sources
- `registered_voters.csv`: Master list of registered voters.
- `northgate_early_inperson.csv`: Early voting records for Northgate county.
- `southfield_early_inperson.xlsx`: Early voting records for Southfield county.
- `mail_ballots.xlsx`: Combined mail-in ballot returns.
- `precincts.geojson`: Geographic boundaries for precincts.
- `first_round_may.csv`: Voter participation records from the May election.

## Methodology
1. **Load:** Ingest raw CSV and Excel files containing voter and ballot data.
2. **Clean:** Normalize voter IDs and standardize date formats across different datasets.
3. **Merge:** Combine early voting, mail-in, and registration data.
4. **Analyze:** Calculate turnout rates and track voter retention from the May election.

---
*Analysis Date: June 08, 2026*
