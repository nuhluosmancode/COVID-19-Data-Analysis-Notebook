COVID-19 Data Analysis Notebook
Overview

This repository contains a Jupyter Notebook for analyzing COVID-19 data. The notebook performs exploratory data analysis (EDA) on a dataset of COVID-19 cases, visualizing trends over time and summarizing key statistics for specified countries.
Contents

    covid_analysis_notebook.ipynb: The Jupyter Notebook file containing the code and analysis.

Dataset

The dataset used in this analysis includes daily COVID-19 case counts for various countries. Key columns in the dataset include:

    Country/Region: Name of the country or region.
    Date: Date of the reported cases.
    Other columns represent daily case counts for specific dates.

Analysis

The notebook includes the following analyses:

    Data Loading and Cleaning:
        Loading the dataset into a Pandas DataFrame.
        Dropping irrelevant columns.
    Summary Statistics:
        Displaying summary statistics for specified countries.
    Visualizations:
        Plotting total cases over time for specified countries.
        Generating descriptive statistics for the filtered dataset.

Requirements

To run this notebook, you need to have the following Python packages installed:

    pandas
    numpy
    seaborn
    matplotlib

You can install these packages using pip:

pip install pandas numpy seaborn matplotlib

Usage

    Clone the repository:

    bash

git clone https://github.com/nuhluosmancode/covid-analysis-notebook.git

Navigate to the project directory:

bash

cd covid-analysis-notebook

Open the Jupyter Notebook:

bash

jupyter notebook covid_analysis_notebook.ipynb

Run the cells to perform the analysis.
