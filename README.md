# Global Health Archetypes Using PCA and K-Means

## Project Description
This project analyzes global health and socioeconomic indicators using PCA and K-means clustering. The goal is to identify country-level health archetypes and examine how they differ in life expectancy, GDP per capita, and disease burden.

## Files Included
- `Uncovering_Global_Health.ipynb`: main analysis notebook
- `Life_Expectancy_Data.csv`: WHO life expectancy dataset
- `life_expectancy.csv`: World Bank socioeconomic dataset
- `final_clustered_dataset.csv`: final dataset after merging, cleaning, PCA, and clustering
- `cluster_profiles.csv`: summary profile of the identified clusters
- `cluster_evaluation.csv`: clustering evaluation results
- `external_validation.csv`: external validation results against income group and region
- `descriptive_statistics.csv`: descriptive statistics table
- `missing_values.csv`: missing-value summary
- `outlier_detection.csv`: outlier-detection summary
- `correlations_with_life_expectancy.csv`: correlations with life expectancy
- `pca_loadings.csv`: PCA loading values
- `vif_full_model.csv`: VIF results for the full regression model
- `regression_full_model.txt`: full regression model output
- `regression_refined_model.txt`: refined regression model output
- `regression_robustness_no_AM.txt`: robustness regression output excluding Adult Mortality
- `fig1_life_expectancy_overview.png` to `fig13_external_validation.png`: generated figures used in the report

## How to Run the Notebook
1. Download or clone this repository.
2. Open `Uncovering_Global_Health.ipynb` in Jupyter Notebook or JupyterLab.
3. Make sure the two input datasets are in the same folder as the notebook:
   - `Life_Expectancy_Data.csv`
   - `life_expectancy.csv`
4. Run all cells from top to bottom.
5. The notebook will reproduce the data cleaning, merging, regression analysis, PCA, K-means clustering, external validation, summary tables, and figures.

## Python Packages Used
- pandas
- numpy
- scikit-learn
- statsmodels
- matplotlib
- seaborn
- scipy

## Reproducibility Notes
The K-means model uses `random_state = 42` and `n_init = 10`. Country-name harmonisation was applied inside the notebook before merging the datasets.

## Author
Ahmad Almalkawi
