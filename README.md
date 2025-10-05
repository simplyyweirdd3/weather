# Weather Comparison Project

This project compares rainfall data in **Seattle, St. Louis, and New Orleans**  
The dataset includes daily precipitation totals for Seattle and St. Louis, and yearly totals for Mumbai.  
We clean, visualize, and analyze the data to understand rainfall patterns across different regions.

## Data sources
- `data/seattle_rain.csv` — Seattle precipitation (source: class GitHub)
- `data/stl_rain.csv` — St. Louis precipitation (source: class GitHub)
- `data/new_orleans.csv` — New Orleans precipitation (source: class GitHub)

## Data Sources
- Seattle data: [DATA 5100 GitHub Repository – Seattle Rain Data](https://github.com/bfischer/data5100-weather)  
- New Orleans data: [NOAA Climate Data Online (CDO) – New Orleans Station (USW00012916)](https://www.ncei.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00012916)

## Data Analysis

The analysis was performed in `Code/Weather_Data.ipynb`.  
The clean dataset created during the process is saved as `Data/clean_precipitation_sea_no.csv`.  
The main visualisation (`Reports/annual_totals_sea_no_barchart.png`) compares yearly precipitation totals between Seattle and New Orleans from 2018–2022.


## Commands Used
# Step 1: Create project folder and subfolders
mkdir weather
cd weather
mkdir data code reports

# Step 2: Add README.md and requirements.txt
echo "# Weather Comparison Project" > README.md
echo "pandas>=1.5\nmatplotlib>=3.6" > requirements.txt

# Step 3: Download datasets and move them into data/
# (seattle_rain.csv, stl_rain.csv from GitHub repo, new_orleans.csv)

# Step 4: Create Jupyter notebook in code/
# (Weather_Data.ipynb created and plot generated)

# Step 5: Initialize git
git init
git add .
git commit -m "Initial project setup with data, notebook, and CSVs"

# Step 6: Connect to GitHub repo
git remote add origin https://github.com/simplyyweirdd3/weather.git
git branch -M main

# Step 7: Push to GitHub
git push -u origin main


## Project structure
- `data/` — raw and processed data
- `code/` — Jupyter notebook(s)
- `reports/` — plots and exported figures

## Author
Ruman Sidhu
