# Weather Comparison Project

This project compares rainfall data in **Seattle, St. Louis, and New Orleans**  
The dataset includes daily precipitation totals for Seattle and St. Louis, and yearly totals for Mumbai.  
We clean, visualize, and analyze the data to understand rainfall patterns across different regions.

## Data sources
- `data/seattle_rain.csv` — Seattle precipitation (source: class GitHub)
- `data/stl_rain.csv` — St. Louis precipitation (source: class GitHub)
- `data/new_orleans.csv` — New Orleans precipitation (source: class GitHub)

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
