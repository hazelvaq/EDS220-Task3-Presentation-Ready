# Santa Barbara 2017 Thomas Fire Visualization and AQI

## About 
This repository contains a notebook `santa_barbara_thomas_fire.ipynb` about creating a time series showing Averaged Air Quaility Index(AQI) for Santa Barbara, California in 2017 to observe the affects of the Thomas Fire. As well as creating a raster map of Santa Barbara fire scar from the Thomas fire.

## Visualizations
A time series plot from 2017 to 2018, with a moving average of 5-days was created on Santa Barbara's daily AQI levels. As well as, a false color image of Santa Barbara highlighting the fire scar from the aftermath of the Thomas fire. These maps are located in the images/directory.

## Highlights
- Fetch vector data from online repository
- Data wrangling with `pandas`
- Time series analysis with `matplotlib`
- Raster wrangling with `rioxarray`
- Plotting and customizing a fasle color raster image

## Data
Environmental Protection Agency (2023), *Air Quality Data Collected at Outdoor Monitor Stations* [`daily_aqi_by_cbsa_2017.zip`, `daily_aqi_by_cbsa_2018.zip`] from (https://www.epa.gov/outdoor-air-quality-data). Accessed date: November 25,2023

California Govt State Geoportal (2023), *California Fire Perimeter*, [Data file] from https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about. Accessed date: November 25,2023

Microsoft Planetary Computer (2023), *Landsat C2-12*, [Data file] from (https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2). Accessed date: November 25, 2023
