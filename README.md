# Agri_Food_CO2_Emission
# Introduction

This project explores the spatial distribution and temporal trends of CO2 emissions in the agri-food sector, providing insights into geographic patterns and changes over time. Additionally, it investigates the relationship between CO2 emissions and local temperature changes.

# Key Questions 

Which countries have the highest/lowest CO2 emission from the agri-food sector ?

Which countries have the highest/lowest per capita CO2 emission from the agri-food sector ?

What trend does the global CO2 emission from the agrifood sector show?

What trend does the global per capita CO2 emission from the agri-food sector show?

What is the relationship between total/per capita CO2 emission, and the change in local average temperature?


# Data set

The data used in this case study was sourced from Kaggle.
- **Dataset title**: Agri-Food CO2 Emission Dataset

- **Author**: Alessandro Lo Bello 

- **URL**: [Dataset on Kaggle](https://www.kaggle.com/datasets/alessandrolobello/agri-food-co2-emission-dataset-forecasting-ml/data)

- **Contains**: 6965 rows & 31 columns

- **Temporal coverage**: 1990-2020

- **Geospatial coverage**: Worldwide
    
Additionally a JSON file containing countries geographic data is sourced from [world-countries-json](https://www.kaggle.com/datasets/ktochylin/world-countries) and used for geospatial analysis. 

## Steps of the Analysis

- **Jupyter notebooks and the Anaconda libraries manager** were used for analysis.

- **Analysis has been conducted using Python along with the following libraries and modules**:
  - **pandas**: For data manipulation and analysis.
  - **numpy**: For numerical operations and array handling.
  - **matplotlib**: For creating visualizations.
  - **seaborn**: For statistical data visualization and enhancement of `matplotlib` plots.
  - **folium**: For generating interactive maps.
  - **statsmodels.api**: For statistical models.
  - **scikit-learn**:
    - **`sklearn.model_selection`**: For splitting datasets.
    - **`sklearn.linear_model`**: For linear regression.
    - **`sklearn.metrics`**: For evaluating model performance.

- **Descriptive analyses** have been conducted after importation of data.

- **Data consistency checks**:
  - Mixed type data
  - Missing data
  - Duplicates
  - Outliers have been identified and addressed accordingly.

- **Data wrangling**:
  - Improved data integrity
  - Created new variables relevant for the analysis
  - Standardized the dataset by excluding geographic areas with few data

- **Inconsistencies in naming of geographical areas** in the dataset and JSON file were addressed.

- **Geospatial analysis** using a JSON file has been conducted.

- **Time series analysis** has been conducted.

- **Supervised machine learning** has been conducted.

- **Visual analysis** was conducted using Tableau, and a storyboard was created to communicate the insights and findings.You can access the storyboard 
[here](https://public.tableau.com/shared/5P3MHR3GB?:display_count=n&:origin=viz_share_link) on Tableau Public.







