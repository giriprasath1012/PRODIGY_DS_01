# PRODIGY_DS_01
# World Population Data Analysis Project

## Overview

This project involves the analysis and visualization of world population data. The dataset, named 'worlddb.csv', is used to explore trends in population growth over multiple years for various countries.

## Data Cleaning

The initial steps include loading the dataset using pandas, checking for missing values, and dropping unnecessary columns. In this case, the '1960' column is dropped as it may not contain relevant data for the analysis.

Missing values in subsequent years (from 1961 to 2022) are replaced with the mean value of each corresponding column, ensuring a more complete dataset for analysis.

## Data Visualization

The project includes a simple data visualization component that allows users to input a country name and a range of years. The Python script uses matplotlib to generate a bar chart illustrating the population trend for the specified country within the given year range.


## Dependencies

- pandas
- matplotlib

## Dataset

The dataset used for this project is 'worlddb.csv', which contains information on world population for various countries over multiple years.

