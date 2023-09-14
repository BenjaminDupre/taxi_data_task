# Taxi Data Task

## Problem Statement
The attached dataset contains a sample from the Yellow Taxi Trip Records Data Set provided by the TLC of NYC. The data dictionary can be found [here](data_dictionary_link). Your task is to analyze the data and extract insights and trends. You are free in how to approach this, but feel free to clean, impute, feature engineer, and visualize as much as needed. Please provide your assignment within a well-documented Jupyter Notebook that also contains a management summary of your results.

## Management Summary

Here you can find the [Jupyter Notebook](https://github.com/BenjaminDupre/taxi_data_task/blob/main/taxi_data.ipynb), structured in the following manner:

- Loading
- Data Cleaning & Imputation
- Feature Engineering
- Exploratory Data Analysis
- Analysis

It answers the question of which factors are most important for estimating the total amount of one taxi drive. Parallels are made in the EDA section with the overall performance of the industry.

**In a nutshell:**

For each individual ride, the most important factors determining the Amount ($ USD) are (1) trip distance, (2) tip amount, and (3) the trip being Coded to JFK.

Overall, the industry has seen a steady decline in ridership (-15% approximately) since the beginning of 2018. This decline is stebalizing after the significant drop in passenger numbers during the COVID-19 pandemic.

Nonetheless, there is reason for optimism in the sector overall. The amount in USD seems to be increasing. In the more optimistic scenario, it has increased by 47% in nominal USD. When correcting for inflation and on a per-mile basis, it has increased by 10%. However, this worst-case scenario must be taken with caution, as it relies heavily on the last two exceptionally good months of January 23 & February 23.

