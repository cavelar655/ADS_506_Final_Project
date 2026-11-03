# ADS-506 Final Team Project

University of San Diego  
ADS-506: Applied Time Series Analysis

## Team Members
- Asher Frank
- Cassandra Avelar
- Kalixta Escoto

## Project Overview
This project explores time series forecasting using the
City of San Diego's Get It Done service request data.

Our preliminary research focuses on trends, seasonality,
and forecasting municipal service request volumes.
The final research question and modeling approach
will be determined following exploratory analysis.

## Data
Source: [San Diego Get It Done Reports](https://data.sandiego.gov/datasets/get-it-done-reports/)

The `data/` directory contains compressed CSV files
organized by council district.

Files are stored as `.csv.gz` to reduce repository size.
R can read these directly using `readr::read_csv()`.

## Tools
- R
- tidyverts (`tsibble`, `feasts`, `fable`)
- Quarto
- GitHub

## Repository Structure
- `data/` — Compressed source datasets (`.csv.gz`)
- `notebooks/` — Exploratory analysis, forecasting experiments, and working Quarto (`.qmd`) files