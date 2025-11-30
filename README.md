# Reduced Daylight, Not Weather: The Fundamental Driver of Stockholm’s Network-Wide Cycling Decline Post-Autumn Break (2015–2023)

## Introduction
This analysis examines how cycling patterns in Stockholm change around höstlov (week 44), which coincides with Sweden’s switch to wintertime. It explores how daylight, route types, weather, and the traffic environment influence these changes. The results highlight actions that Stockholm Stad, Trafikverket, and Cykelfrämjandet can take to better support cyclists during the clock change and darker evenings, and identify areas where their current practices can be improved.

## Main notebook:
Cycling_Analysis.ipynb

## Project Files

### Analysis & Data
Cycling_Analysis.ipynb             # Main analysis
td_cykel_15_min_2015-2024.csv      # Cycling counts (15 min intervals)
platser_cykel_2015-2024.csv        # Counter location metadata
stockholm_dst_end_2015_2025.csv    # DST transition dates
README.md                          # Documentation

### GIS Files
belysning.qgz                      # QGIS project (map styling, layers, analysis)
Cykelstrak_Linje.gpkg              # GeoPackage containing cycle route geometries

### Route Images (Static Exports)
Hjorthagen.png
Magelungsvägen.png
Örbyleleden.png
These images show selected cycle paths used in the spatial analysis (lighting conditions and route context)


## What the Analysis Covers
Data cleaning & preparation
Convert timestamps, extract time features, build daily/weekly/monthly datasets.

Seasonal and daily patterns
Monthly totals, yearly comparisons, daily cyclists vs. sunrise/sunset.

Hourly patterns
Heatmaps and distributions showing commuting peaks.

Week 43 → Week 44 analysis
Absolute and percentage drops across years, route-level differences, and time-of-day effects.

Route-level behaviour
Identification of paths with the largest drops (absolute, percentage, weighted).

## Key Descriptive Insights
- Decline is network-wide, not due to weak general lighting.
- Cycling reliably drops 3–19% post-höstlov.
- Three opposing cycle paths create 14% of volume loss.
- The drop is daylight-driven, not weather-related

## How to Run
Install dependencies:
pip install pandas numpy matplotlib seaborn plotly pytz astral scipy

Open the notebook:
jupyter notebook
Or run directly in VS Code with the Jupyter extension.

## Dependencies
pandas
numpy
matplotlib
seaborn
plotly
pytz
astral
scipy
