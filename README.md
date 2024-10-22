# Big-data-and-data-mining
Big Data and Data Mining (Autumn 2024)

# Lab 01: Data Analysis with Pandas

## Overview

**Lab 01** is a comprehensive introduction to data manipulation and analysis using Python's `pandas` library. This lab is divided into three parts:

- **Part A** focuses on creating DataFrames, slicing, filtering, and basic manipulations.
- **Part B** delves into advanced data wrangling techniques like `groupby` operations, filtering, and creating pivot tables.
- **Part C** involves data cleaning, visualization, and exploratory data analysis (EDA) using a dataset from the City of Berkeley, containing police call records.
Large data sets can be automatically downloaded in the program！

## Learning Objectives

By working through all three parts of this lab, you will learn to:
- Create and manipulate `pandas` DataFrames.
- Perform data slicing, filtering, and selection with `loc` and `iloc`.
- Aggregate data using `groupby` and compute summary statistics.
- Use pivot tables for multi-dimensional analysis.
- Clean datasets, handle missing data, and transform text fields.
- Visualize data using `matplotlib` and `folium`.

## Dataset Information

The dataset used in Part C is sourced from the City of Berkeley and contains information on calls to the Berkeley Police Department. It includes details such as the nature of the call, location, and time. For more details, visit the dataset link [here](https://data.cityofberkeley.info/Public-Safety/Berkeley-PD-Calls-for-Service/k2nh-s5h5).

## Prerequisites

This lab assumes that you have a basic understanding of Python programming. It is recommended that you watch the lectures on `pandas` before starting. The lab will involve:

- `pandas` for data manipulation.
- `matplotlib` for visualization.
- `folium` for interactive map creation in Part C.

## Lab Structure

### Part A: Introduction to Pandas
- Overview of `pandas` and its importance in data science.
- Creating `DataFrames` from scratch and importing data from CSV files.
- Selecting data using `.loc`, `.iloc`, and boolean arrays.
- Filtering data based on conditions.
- Renaming columns, dropping rows/columns, and modifying DataFrames.
- Hands-on exercises to solidify understanding of basic operations.

### Part B: Data Aggregation and Grouping
- Using `groupby` to split data into groups and aggregate them.
- Applying functions like `.mean()`, `.max()`, and `.agg()` to grouped data.
- Method chaining for efficient data manipulation.
- Creating pivot tables to summarize data.
- Analyzing election datasets by grouping data based on conditions like political parties.

### Part C: Data Cleaning and Exploratory Data Analysis (EDA)
- Acquiring and preparing the Berkeley Police Department call dataset.
- Cleaning data, including handling missing values and transforming columns.
- Extracting latitude and longitude from text fields for geographic analysis.
- Visualizing trends in data using `matplotlib` and creating interactive maps with `folium`.
- Performing EDA to uncover insights from the dataset.


## How to Use

1. Clone the repository or download the notebook files (`lab01A.ipynb`, `lab01B.ipynb`, `lab01C.ipynb`).
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas matplotlib folium
   ```
3. Open the notebooks using Jupyter:
   ```bash
   jupyter notebook lab01A.ipynb
   ```
4. Follow the instructions in each notebook, complete the exercises, and ensure all answers are correct before submission.

## Important Notes

- **Documentation Tip**: Use `shift+tab` in Jupyter to view method documentation while coding. This can help understand the parameters and expected input for `pandas` functions.
- **Learning Curve**: Pandas can be complex, especially for beginners. Refer to the official documentation and practice regularly for better understanding.
- **Real-world Application**: Data cleaning and EDA skills are crucial in real-world data science projects. The tasks in this lab will prepare you for working with messy datasets and extracting meaningful insights.

## Acknowledgments

- Data provided by the City of Berkeley Open Data portal.
- This lab is part of a series aimed at building proficiency in data analysis using Python.

## License

This project is licensed under the MIT License.
