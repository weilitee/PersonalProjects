# Crime Analysis in Minneapolis (2019–2025)

This project explores crime trends in Minneapolis from 2019 through 2025.  The goal is to provide an interactive dashboard that helps residents, policy makers and researchers understand where and when crimes occur, and how those patterns evolve over time.

## Overview

Publicly available incident data from the Minneapolis Police Department is cleaned and aggregated using Python.  The processed data is then visualized in a Tableau dashboard that allows users to interact with the data: filter by offence type, drill into neighbourhoods and compare yearly trends.

## Getting started

1. **Data:** The raw incident data can be downloaded from the Minneapolis open data portal or via the Kaggle notebook linked below.  A cleaned dataset (e.g. `crime_data_cleaned.csv`) is included in the `data/` folder.
2. **Data cleaning:** If you wish to reproduce the cleaning steps, open the `kaggle_notebook.ipynb` notebook in Jupyter or Kaggle.  It uses pandas to standardize date formats, merge auxiliary datasets and compute metrics.
3. **Dashboard:** Open `crime_analysis.twb` in Tableau Public or Tableau Desktop.  When prompted, connect it to the cleaned dataset from step 1.
4. **Explore:** Use the controls on the dashboard to filter by crime type, year and neighbourhood.  Hover over charts to view tooltips and additional details.

## Key features

- **KPI summary:** Compares the current crime rate to the baseline year 2019 with directional indicators.
- **Incident filter:** Select specific crime categories such as Auto Theft or Robbery; all visualizations update accordingly.
- **Neighbourhood view:** Heat map highlighting neighbourhoods with the highest incident counts.
- **Trend analysis:** Time‑series charts showing how incident counts change from 2019 to 2025.
- **Crime type breakdown:** Bar charts comparing the relative frequency of different offence types and how they shift over time.

## Resources

- **Kaggle notebook:** [Crime Analysis — data cleaning and preparation](https://www.kaggle.com/code/weilitee/crime-analysis-v1) (external)
- **Tableau dashboard:** Link to your published Tableau dashboard, if available

Feel free to use this project as a template for similar analyses in other cities or time periods.  Contributions and suggestions are welcome.
