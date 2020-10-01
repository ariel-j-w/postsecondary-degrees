# Postsecondary Degrees
Investigation of demographics of those receiving various levels of postsecondary degrees conferred in the United States across multiple years.

Currently this project is a work in progress, and much future work is expected.

## Pre-processing
The file `pre-processing.Rmd` brings in the raw data retrieved from from the [National Center for Education Statistics](https://nces.ed.gov/programs/digest/current_tables.asp) and creates tidy tables of data. This file transforms:
- `tabn324.20.csv` into `doctoral.csv`
- `tabn323.20.csv` into `masters.csv`
- `tabn322.20.csv` into `bachelors.csv`

## Exploratory Data Analysis
The file `eda.rmd` has a variety of exploratory visualizations intended to orient us with the data and identify areas where we want to dig deeper. We look for initial trends, and here we value efficient visualization over in-depth analysis.

## Data
Unless otherwise indicated, all data was retrieved from publicly available tables from the [National Center for Education Statistics](https://nces.ed.gov/programs/digest/current_tables.asp), which is sponsored by the U.S. Department of Education.
