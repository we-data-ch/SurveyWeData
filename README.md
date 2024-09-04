# Survey Data Cleaning and Analysis

This project focuses on cleaning and analyzing survey data using R. 
The process includes renaming columns for clarity and visualizing categorical variables.

## Structure

- `data/`: Contains the raw and cleaned data files.
- `scripts/`: R scripts for data processing and visualization.
- `README.md`: Project overview and instructions.

## Requirements

- R < 4.1
- Packages: `tidyverse`, `janitor`, `here`, `pacman`

## Key Steps

1. **Data Cleaning:**
   - Renames long column names for easier reference.
   - Converts character variables to factors where appropriate.

2. **Data Visualization:**
   - Generates bar plots for categorical variables with more than 8 categories.
   - Excludes `NA` values from plots and notes the count below each plot.

## Usage

Run the quarto report to process the data and generate visualizations.
