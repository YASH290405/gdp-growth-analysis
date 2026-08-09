# GDP Growth Analysis (1960–2016)

Exploratory data analysis of global GDP trends using the World Bank GDP dataset, covering 256 countries and regions from 1960 to 2016.

## Overview

This project loads raw GDP values by country and year, computes year-over-year GDP growth rates, and produces interactive visualizations to compare growth trajectories across countries and regions over nearly six decades.

## Dataset

- **Source:** World Bank GDP dataset
- **Coverage:** 256 countries/regions, 1960–2016
- **Fields:** Country Name, Country Code, Year, GDP Value (current US$)

## What this notebook does

- Loads and cleans the raw GDP dataset with Pandas
- Explores dataset structure (unique countries, year range, summary statistics)
- Computes year-over-year **GDP growth rate (%)** for each country
- Visualizes individual country GDP trends over time
- Compares GDP growth across all countries on a single interactive chart
- Generates standalone HTML visualizations per country using Plotly
- Analyzes GDP growth trends across the full 1960–2016 window for countries with complete data

## Tools & Libraries

- Python
- Pandas — data manipulation and cleaning
- Plotly (Express + Offline) — interactive charting and HTML export

## How to run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install pandas plotly
   ```
3. Update the dataset path in the notebook to point to your local copy of `gdp_data.csv`
4. Open `GDP_Analysis.ipynb` in Jupyter and run all cells

## Sample Output

Running the notebook generates:
- A combined GDP comparison chart across all countries
- Individual interactive HTML charts per country (saved to a local folder)
- A filtered GDP growth comparison for countries with a complete 1960–2016 record

## Author

Yash — SRM Institute of Science and Technology
