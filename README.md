# matplotlib-challenge

# Pymaceuticals Analysis

## Overview

This project analyzes data from a study on the treatment of squamous cell carcinoma (SCC) in mice using different drug regimens. The analysis focuses on the drug regimen Capomulin, examining the effect of mouse weight on tumor volume and other metrics. Various visualizations, including scatter plots, box plots, pie charts, and bar charts, are used to summarize the data.

### Tools Used:

* Python
* Pandas
* Matplotlib
* SciPy

## Files

* **Mouse_metadata.csv** : Contains metadata about the mice used in the study.
* **Study_results.csv** : Contains tumor volume observations and other data from the study.
* **pymaceuticals_starter.ipynb** : The Jupyter Notebook used for data cleaning, visualization, and analysis.

## Analysis Summary

The analysis includes the following key points:

1. Calculated summary statistics (mean, median, variance, standard deviation, SEM) for each drug regimen.
2. Generated bar charts and pie charts to visualize the drug regimens and gender distribution of the mice.
3. Performed quartile analysis to find potential outliers in tumor volumes and displayed them using box plots.
4. Created scatter plots to analyze the relationship between mouse weight and average tumor volume for the Capomulin treatment regimen.
5. Performed correlation and linear regression analysis on mouse weight and tumor volume for Capomulin-treated mice.

## Key Findings

1. The drug regimen Capomulin appears to be effective in reducing tumor size, as indicated by the line plot showing tumor volume decreasing over time for a specific mouse.
2. A strong positive correlation (correlation coefficient: `0.84`) was found between mouse weight and average tumor volume, suggesting that heavier mice tend to have larger tumor volumes.
3. Some outliers were detected in the tumor volume distributions for the drug regimens, indicating potential irregular responses to the treatments.


## External Resources

During the completion of this project, the following external resources were referenced:

### Documentation & Libraries:

* **[Pandas Documentation]()** : Used for general DataFrame manipulation, including `groupby`, `agg()`, and data filtering.
* **[Matplotlib Documentation]()** : Used for generating visualizations, including line plots, scatter plots, pie charts, and box plots.
* **[SciPy Documentation]()** : Used for statistical analysis, including correlation coefficients and linear regression.
* **[Seaborn Documentation]()** : Referenced for advanced data visualization and outlier detection techniques.

### Coding Resources:

* **[Stack Overflow](https://stackoverflow.com/)** : Referenced for troubleshooting and code optimization tips, particularly for Pandas and Matplotlib.
* **[Real Python](https://realpython.com/)** : Used for tips and tutorials on Python, Matplotlib, and Pandas.
* **[Geeks for Geeks](https://www.geeksforgeeks.org/)** : Utilized for general Python syntax and examples, especially related to data visualization.
* **[W3Schools Python]()** : Consulted for quick references and Python tutorials.

### Research & Data Analysis:

* **[Kaggle](https://www.kaggle.com/)** : Used for insights into how to structure and clean datasets, particularly for cancer treatment studies.
* **[Towards Data Science](https://towardsdatascience.com/)** : Consulted for articles on data science best practices and tutorials for handling large datasets.

### Data Cleaning & Preprocessing:

* **[Python.org](https://www.python.org/doc/)** : Official Python documentation for syntax and built-in functions used during data cleaning.
* **[Mode Analytics SQL Guide]()** : While this project didn't directly involve SQL, Mode Analytics provided helpful insights into data structuring and data queries that are useful in general analysis.
