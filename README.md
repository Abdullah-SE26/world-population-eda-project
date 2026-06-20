# World Population EDA Project

This repository contains an exploratory data analysis project for world population data. The analysis is built around a single Jupyter notebook, `01_exploratory_analysis.ipynb`, and uses population, geographic, and demographic metrics for countries across multiple years.

## Project Overview

The goal of this project is to explore global population trends, compare countries and continents, and identify relationships among population, area, density, growth rate, and share of world population. The notebook demonstrates data loading, cleaning checks, summary statistics, correlation analysis, and visualization.

## Dataset

The dataset is stored in `data/world_population.csv` and includes:

- `Rank`
- `CCA3`
- `Country`
- `Capital`
- `Continent`
- `2022 Population`
- `2020 Population`
- `2015 Population`
- `2010 Population`
- `2000 Population`
- `1990 Population`
- `1980 Population`
- `1970 Population`
- `Area (km²)`
- `Density (per km²)`
- `Growth Rate`
- `World Population Percentage`

The dataset contains 234 country-level records and covers population values for several years, along with country metadata such as area, population density, and global population share.

## Analysis Steps

The notebook performs the following analysis:

1. Load the dataset with pandas.
2. Display dataset information, summary statistics, and data quality checks.
3. Count missing values and unique values.
4. Identify the top countries by 2022 population and world population percentage.
5. Compute numeric correlations and visualize them with a heatmap.
6. Group data by continent and compare average population values.
7. Plot continent-level population trends and country-level distributions.

## Tools and Libraries

- Python
- pandas
- matplotlib
- seaborn

## How to Use

1. Open `01_exploratory_analysis.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the notebook cells in order.
3. Inspect the visualizations and summary tables for insights into global population patterns.

## Notes

- The notebook is focused on exploratory analysis rather than predictive modeling.
- The dataset can be extended with additional years or regional breakdowns for deeper analysis.
