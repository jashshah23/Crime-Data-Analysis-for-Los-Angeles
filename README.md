# Crime-Data-Analysis-for-Los-Angeles
This repository provides an in-depth analysis of Los Angeles crime data to uncover spatial, temporal, and demographic patterns and trends. A machine learning model is also developed to predict arrest events.

# Problem Statement
Crime imposes substantial systemic and individual costs in the city of Los Angeles. Recent trends indicate nearly 250,000 incidents per year with an aggregate economic burden estimated at $1.3B annually. This repository aims to harness advanced analytics on detailed open data to derive actionable insights and predictive capabilities that can inform data-driven policies for public agencies to establish sustainable reductions in crime rates.

# Project Overview

Data source: Official crime data published by the LAPD

Time period: January 2020 - December 2023

Number of records: Over 800,000 reported crime incidents

Technologies used: Python, Pandas, Matplotlib, Seaborn, Plotly, Folium, CatBoost

# Project Duration
Start Date- October 31, 2023

End Date-Dec 5, 2023 

# Key Files
Crime_data_analysis.ipynb: A well-documented Jupyter notebook containing the data preprocessing, exploratory data analysis, and predictive modeling.

Preprocessed_data.csv:     The cleaned and preprocessed dataset on which all analysis has been performed.

Models/arrest_model.pkl:   A trained CatBoost model for predicting arrests from crime incidents.

# README.md: The file you are currently reading, providing an overview of the project.

# Repository Structure

The data folder contains both the raw, immutable data sourced from the Los Angeles Police Department, as well as the preprocessed data used for downstream analyses and modeling.

The src folder houses the source code, segmented into Python scripts based on functionality like data preprocessing, visualization, and building machine learning models.

The notebooks folder holds the narrative Jupyter notebooks that perform exploratory analysis and modeling evaluation.

The reports folder stores final analytic summaries, figures and presentation content, while logs contains experiment metadata.

This structure ensures reproducibility, maintains separation of concerns across analytic tasks, and facilitates code modularization.

# Replication Guide
To fully reproduce analysis:

1.conda env create -f environment.yml

2.conda activate crime-env

3.Run Jupyter notebook notebooks/crime_analysis.ipynb
