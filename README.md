# ASEAN Olympic Performance Intelligence System

## Project Overview

This capstone project analyses historical Olympic participation and medal
performance among ASEAN countries from 1924 to 2016.

The system combines Python-based data preparation and exploratory analysis
with an interactive Power BI dashboard.

## Business Challenge

Historical Olympic data contains repeated athlete-event records, team-event
medal duplication and missing demographic information. This makes direct
country and sport comparisons difficult without consistent cleaning and
measurement rules.

## Research Objectives

1. Analyse participation and medal trends.
2. Benchmark performance across ASEAN countries.
3. Identify medal-producing sports.
4. Examine gender differences.
5. Analyse athlete age profiles.
6. Identify emerging or declining performance areas.
7. Highlight areas for further medal-opportunity analysis.

## Tools Used

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Power BI
- Microsoft PowerPoint

## Dataset

The cleaned ASEAN dataset contains:

- 3,233 athlete-event records
- 1,964 unique athletes
- 10 ASEAN countries
- 31 sports
- 90 deduplicated official medals
- Historical records from 1924 to 2016

## Key Findings

- Indonesia and Thailand each recorded 30 official medals.
- Badminton, weightlifting and boxing contributed 70 of the 90 medals.
- Female participation reached 49.6% of ASEAN Summer athlete-event
  participation in 2016.
- The median age was 24.5 years for medal records and 23 years for
  non-medal records, with substantial overlap between the distributions.
- Summer records represented 3,219 of the 3,233 athlete-event records.

## Dashboard Preview

![Executive Overview](images/Executive_Overview.png)

![Performance Analysis](images/Performance_Analysis.png)

## Repository Contents

- `notebooks/01_Data_Cleaning.ipynb` – data preparation and validation
- `notebooks/02_Exploratory_Analysis.ipynb` – exploratory analysis
- `data/asean_olympics_clean.csv` – cleaned ASEAN athlete-event data
- `data/asean_official_medals.csv` – deduplicated official medal data
- `dashboard/ASEAN_Olympics_Dashboard.pbix` – Power BI dashboard
- `presentation/ASEAN_Olympics_Presentation.pptx` – project presentation

## Limitations

- The historical dataset ends in 2016.
- Funding, coaching and training variables are unavailable.
- Athlete-event records may contain repeated athletes.
- Some age, height and weight values are missing.
- The findings identify historical patterns and do not establish causation.

## Author

Terence Quek  
SCTP Associate Data Analyst Capstone Project
