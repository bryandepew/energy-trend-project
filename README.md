# Energy Trend Project

Analysis of U.S. energy generation trends across the South Atlantic region, using data from the U.S. Energy Information Administration (EIA).

## What it does
Cleans and categorizes EIA power plant and net generation data into major fuel types (solar, wind, hydro, natural gas, coal, petroleum/oil, and biomass/waste). Joins the results to state-level geospatial boundaries to visualize each state's predominant energy source over time, and tracks generation trends by fuel type and state from 2005-2025.

## Tools used
R, tidyverse, dplyr, data.table, ggplot2, sf, tigris

## Key outputs
- Faceted map showing each South Atlantic state's predominant fuel type across five-year intervals (2005, 2010, 2015, 2020, 2025)
- Time-series line charts of energy generation by state for coal, natural gas, petroleum/oil, and biomass/waste sectors

## Data source
U.S. Energy Information Administration (EIA) - plant-level and net generation datasets