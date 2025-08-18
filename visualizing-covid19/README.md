# Visualizing COVID‑19 Trends

The aim of this project is to visualize and understand the global progression of the COVID‑19 pandemic.  By cleaning, aggregating and plotting publicly available data, the project produces clear and informative charts that track cases, deaths and vaccinations over time and across regions.

## Overview

COVID‑19 data, such as daily case counts, deaths and vaccination numbers, is sourced from trusted public repositories.  The data is cleaned and transformed in R using the `tidyverse` suite.  Visualizations are created with `ggplot2` to highlight important patterns and trends.

## Project structure

- `R/covid19_visualization.R` – Main script for data processing and plotting.
- `data/` – Directory containing the cleaned COVID‑19 dataset (e.g. `covid_data_cleaned.csv`).
- `figures/` – Output directory where the generated plots are saved.
- `README.md` – Project description and instructions (this file).

## Requirements

- R 4.0 or later
- Packages: `tidyverse`, `ggplot2`, optionally `lubridate`

## Running the analysis

1. Clone or download this repository and navigate to the `visualizing-covid19` directory.
2. Install the required R packages: `install.packages("tidyverse")`.
3. Open `R/covid19_visualization.R` in RStudio or a compatible environment.
4. Execute the script to generate cleaned data and plots.  Output figures will be saved to `figures/`.

## Highlights

- **Data cleaning:** Handles missing values, standardizes date formats and aggregates daily counts to weekly or monthly time frames.
- **Time‑series plots:** Creates trendlines for cases, deaths and vaccinations, making it easy to see how the pandemic has evolved over time.
- **Regional comparisons:** Uses faceted plots and color scales to compare different countries or regions and identify disparities in pandemic outcomes.

This project serves as a foundation for more advanced pandemic analysis.  You can extend it by adding models, forecasts or additional health metrics.
