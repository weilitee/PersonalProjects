# Super Bowl TV & Halftime Show Analysis

This project examines the relationships between Super Bowl game statistics, television viewership and halftime show performances.  The aim is to uncover interesting patterns in scoring, audience engagement and advertising over the history of the NFL’s premier event.

## Overview

Using R and tidyverse packages, multiple datasets covering Super Bowl games, TV viewership metrics and halftime show performers are combined and cleaned.  Exploratory data analysis and visualizations are then used to answer questions such as:

* How do combined game scores and point differences distribute across years?
* Does the size or composition of halftime shows correlate with viewership?
* How have advertisement costs grown relative to audience numbers?

## Project structure

- `R/super_bowl_analysis.R` – Main analysis script; loads data, performs cleaning, and produces plots.
- `data/` – Raw and intermediate datasets used in the analysis.
- `figures/` – Output directory where plots are saved.
- `README.md` – Project description and usage instructions (this file).

## Requirements

- R 4.0 or later
- Packages: `tidyverse`, `ggplot2`, optionally `readr` and `lubridate`

## Running the analysis

1. Clone or download this repository and navigate to the `super-bowl-tv-halftime-analysis` directory.
2. Install the required R packages if you haven’t already: `install.packages("tidyverse")`.
3. Open `R/super_bowl_analysis.R` in RStudio or your preferred IDE.
4. Execute the script.  It will read the data from `data/`, perform the analysis and write the resulting plots to `figures/`.

## Highlights

- **Distributions:** Histograms illustrate the distribution of combined points scored and point differences across all Super Bowl games.
- **Halftime shows:** Visualizations explore the number of performers and how halftime productions have evolved over time.
- **Advertising vs. viewership:** Line plots compare the growth of advertising costs with audience size to reveal whether bigger budgets translate into more viewers.

By analysing historical Super Bowl metrics, this project demonstrates basic data wrangling and visualization techniques in R.  You can easily extend it by incorporating additional data sources or experimenting with more advanced models.
