# Species Observation Trends with FinBIF R Package

Analyze temporal and geographic patterns of biodiversity observations using the FinBIF R package.

## Overview

This R notebook retrieves occurrence data directly from the Finnish Biodiversity Information Facility (FinBIF) using the official R package and performs a trend analysis. NOTE: you need an API KEY for FinBIF API. The notebook instructs how to get one if you don't have it yet.

## Usage

1. Open `observation_trends_finbif.ipynb` in Jupyter/RStudio
2. Modify query parameters in Step 2 to customize your analysis:
   - `limit_records`: Adjust number of records to retrieve
   - `top_n_species`: Change number of top species to analyze
   - `min_year`: Filter observations by year

3. Execute cells sequentially to run the analysis

## Outputs

- Time series plot showing observation trends
- Interactive map with observation locations
- Summary statistics tables
- Geographic distribution analysis

## Data Source

Data is retrieved from FinBIF (Finnish Biodiversity Information Facility), which aggregates biodiversity observations from various sources in Finland. 

## References

- FinBIF R Package: https://github.com/luomus/finbif
- FinBIF Website: https://laji.fi/en/
