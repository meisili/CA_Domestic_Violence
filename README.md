# California Domestic Violence Data Analysis

## About This Project

This repository contains data cleaning and preparation scripts for analyzing domestic violence trends in California. The cleaned data is used to create interactive visualizations exploring the relationship between domestic violence calls and homicide rates across California counties.

**View the interactive Flourish data visualization here:** [Domestic Violence in California: Calls, Weapons and Fatal Outcomes](https://public.flourish.studio/story/3489659/)

## Data Sources

All data is sourced from the California Department of Justice OpenJustice portal:
- **Domestic Violence Related Calls for Assistance** 
- **Homicide Data**

Source: https://openjustice.doj.ca.gov/data

## Repository Structure
```
CA_Domestic_Violence/
├── notebooks/          # Jupyter notebooks for data exploration and analysis
├── data/
│   ├── raw/           # Original datasets from OpenJustice
│   └── processed/     # Cleaned data ready for visualization
├── scripts/           # Python scripts for data processing
└── README.md
```

## Workflow

1. **Data Collection**: Download raw data from CA DOJ OpenJustice
2. **Data Cleaning**: Use Python scripts and Jupyter notebooks to clean and process data
3. **Data Export**: Generate CSV files optimized for visualization
4. **Visualization**: Import processed data into Flourish for interactive storytelling
