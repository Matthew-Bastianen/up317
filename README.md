# up317
Code for my final project surrounding economic impacts of housing age in Chicago

# UP 317 Final Project: Spatial Autocorrelation Analysis

**Author:** Your Name  
**Date:** Spring 2026  
**Course:** UP 317 - Introduction to Urban Data Science

## Research Question

Does housing exhibit spatial clustering in Mexico City municipalities?

## Data Sources

- **Geographic data:** Mexico City municipality shapefile (INEGI)
- **Housing:** 

## Methods

1. Exploratory spatial data analysis (mapping)
2. Spatial weights matrix (Queen contiguity)
3. Global Moran's I test
4. Local Indicators of Spatial Association (LISA)
5. Sensitivity analysis (p-values, weight specifications)

## Folder Structure

UP317-Final-Project/
├── README.md                 # This file
├── data/
│   ├── raw/                  # Original data (never edit!)
│   └── processed/            # Cleaned data
├── src/                     # Numbered R scripts
├── output/
│   ├── figures/              # Maps and plots
│   └── tables/               # Results tables
└── paper/                    # Final paper

## How to Reproduce

1. Place raw data in `data/raw/`
2. Run scripts in `src/` in numbered order
3. Output saves to `output/`
4. Figures and tables are incorporated into paper in `paper/`

## Key Findings

[To be added after analysis]

## Dependencies

- R version 4.x
- Packages: sf, spdep, tidyverse, tmap

## Contact

mb110@illinois.edu
