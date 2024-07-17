# Amazon-sales-analysis-using-Python

This repository contains a Jupyter notebook that performs data preprocessing, analysis, and visualization on an Amazon sales dataset.

Dataset link: https://www.kaggle.com/datasets/mdsazzatsardar/amazonsalesreport

## Description

The notebook performs the following tasks:
1. **Data Loading**:
     The first step involves loading the sales data from a CSV file using Pandas. The dataset contains 128,976 entries with 21 columns, including information such as Order 
     ID, Date, Status, Sales Channel, Quantity, Amount, and more 
   
2. **Data Preprocessing**:
   The data preprocessing steps include:
   
     1. Dropping unwanted columns.
     2. Handling missing values by filling them with appropriate values or removing rows.
     3. Renaming columns for better readability.
     4. Changing data types for certain columns.
   
4. **Data Analysis**: 
   Descriptive statistics and insights are provided, such as:
     1. Distribution of various sizes ordered.
     2. Most common courier status.
     3. Analysis of order quantities by size.
   
5. **Data Visualization**: Visualizes the data using various plots to uncover trends and patterns.
  The notebook includes various visualizations:
     1. Count plots.
     2. Bar plots.
     3. Histograms.
     4. Count plots.


## Files

- `Amazon sales.ipynb`: Jupyter notebook containing the data analysis and visualization code.
- `Amazon Sale Report.csv`: The dataset used for the analysis.

## Requirements

The following Python libraries are required to run the notebook:
- pandas
- numpy
- matplotlib
- seaborn


You can install the required libraries using the following command:

pip install pandas numpy matplotlib seaborn
