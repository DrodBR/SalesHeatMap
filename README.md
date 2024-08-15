# Sales Analysis by Hour and Department at Alameda Location

## Project Overview

This project analyzes sales data to determine optimal sales times by hour and department at the Alameda location. The goal is to provide insights for improving team scheduling to ensure staff are present during peak sales periods. The analysis is based on a dataset that also includes data for Yellowknife and Bayside, but only Alameda was considered for this project.

## Data Description

- **Dataset Size**: 2,920,438 rows
- **Date Range**: July 1, 2021, to December 31, 2021
- **Locations Included**: Alameda, Yellowknife, and Bayside
- **Location Analyzed**: Alameda

**Excluded Departments**:
  - LICENSED KIOSK
  - CUSTOMER SERVICES
  - DISCOUNT
  - SUSHI
  - CATERING
  - SEAFOOD
  - FLORAL
  - BASKETS

Negative sales amounts were excluded from the analysis to ensure accuracy.

## Objective

**What are the best sales times per hour and department at the Alameda location, so the company can improve team scheduling to be at the right time in the right department?**

## Tools and Libraries

- **Python**: Core language for data processing and analysis.
- **pandas**: For data manipulation and cleaning.
- **matplotlib.pyplot**: For visualizing data.
- **seaborn**: For advanced statistical visualizations.
- **Jupyter Notebook**: For documenting and running the analysis.

## Files

- **Jupyter Notebook**: `SalesByHour.ipynb` - Contains the analysis and visualization code.
- **Data File**: The raw data is split into two parts due to GitHub’s file size limitation:
  - `Sales_By_Hour.zip.part1`
  - `Sales_By_Hour.zip.part2`

## Final Result

Here is an example of a heatmap generated from the analysis:

![Heatmap Example](https://github.com/DrodBR/SalesHeatMap/blob/main/heatmap.png)
