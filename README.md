# Hydrometric Data Analysis Tool

## Overview
This Python script processes hydrometric flow and water level data from the [Water Survey of Canada](https://wateroffice.ec.gc.ca/search/historical_e.html), generating time series visualizations and rating curve analyses to support hydrological modeling and interpretation.

An interactive command-line interface (CLI) allows users to select from four types of plots:

1. **Discharge Time Series**  
   Displays daily discharge over the available time period.

2. **Yearly Discharge and Level Plot**  
   Visualizes discharge and water level together over time for comparison.

3. **Log Rating Curves**  
   Generates log-scale rating curves with data grouped by month, year, and season.

4. **Rating Curve Regression**  
   Fits and plots a regression of the form:  
   \[
   Q = a(h - h_0)^b
   \]  
   to approximate the observed discharge–stage relationship.

---

## Requirements
- A `.csv` file from the Water Survey of Canada containing both flow and water level data  
- Python (3.x) installed  
- A code editor or IDE (e.g., VS Code, PyCharm)

---

## How to Use
1. Download the script and sample `.csv` files (optional for testing).  
2. Update the file path to your `.csv` dataset in the script (see variable `df` near the top of the file).  
3. Run the Python script.  
4. Use the interactive CLI menu to select and display the desired plot.

---

## Sample Data
Sample `.csv` files are included for testing and demonstration purposes.

---

## Data Source
Hydrometric data is obtained from the [Water Survey of Canada](https://wateroffice.ec.gc.ca/search/historical_e.html).
