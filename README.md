# Measles-Infection-Rates
# Course Project: Geographical Variations in Measles Infection Rates (US: 1920-1944)

## Overview

The MeaslesInfectionRate.R script analyzes geographical variations in measles infection rates in the United States from 1920 to 1944. The script reads data from the Dalziel2016_data.csv file, filters it by the specified year range and city regions, calculates infection rates, and visualizes the results.

## Script Execution

To execute the script successfully, follow these steps:

1. Install Required Packages:
   Ensure that the script is run in an environment with R version and install the following package:
   - tidyverse (provides data manipulation and visualization tools)

   The script includes commands to load these packages.

2. Download Data File:
   Download the required data file, [Dalziel2016_data.csv](~/CSB/python/data/), and ensure it is available in your working directory.

3. Adjust File Path:
   Update the path in the `read_csv` command in the script to point to the location where you have saved the Dalziel2016_data.csv file.

## Script Workflow

1. Data Wrangling:
   The script filters the data by the specified year range (1920-1944) and city regions based on the National Geographic regions of the United States. The analyzed regions include the west and southeast.

2. Infection Rate Calculation:
   Infection rates are calculated using the formula: `(infection/population) * 100`. The script calculates infection rates by city and plots them by region.

3. Average Infection Rate:
   The average infection rate is computed for each region and visualized together. The script conducts a t-test to determine the statistical significance of the average infection rates between the two regions. 

## Running the Script

Execute the script in an R statistical programming environment. Ensure that the required packages are installed, and the file paths are correctly specified. The script will generate visualizations and insights into geographical variations in measles infection rates during the specified time period.

## Additional Resources

- [Dryad Dataset](https://doi.org/10.5061/dryad.r4q34): Access the raw data source from Dalziel et al. (2016) on Dryad.
