# global-health-archetypes
PCA and K-means analysis of global health and socioeconomic indicators
# Global Health Archetypes Using PCA and K-Means

## Project Description
This project analyzes global health and socioeconomic indicators using PCA and K-means clustering. The goal is to identify country-level health archetypes and examine how they differ in life expectancy, GDP per capita, and disease burden.

## Files Included
- `Global_Health_Final.ipynb`: main analysis notebook
- `Life_Expectancy_Data.csv`: WHO life expectancy dataset
- `life_expectancy.csv`: World Bank socioeconomic dataset
- `figures/`: generated figures used in the report

## How to Run the Notebook
1. Download or clone this repository.
2. Open `Global_Health_Final.ipynb` in Jupyter Notebook or JupyterLab.
3. Make sure the two CSV files are in the same folder as the notebook.
4. Run all cells from top to bottom.
5. The notebook will reproduce the cleaning, regression, PCA, clustering, validation, and figures.

## Python Packages Used
- pandas
- numpy
- scikit-learn
- statsmodels
- matplotlib
- seaborn
- scipy

## Reproducibility Notes
The K-means model uses `random_state = 42` and `n_init = 10`.
Country-name harmonisation was applied inside the notebook before merging the datasets.

## Author
Ahmad Almalkawi
