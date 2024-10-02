[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Yi0Zbe2y)
# MAST30034 Project 1 README.md
- Name: `Can Senyurt`
- Student ID: `1079752`

**Research Goal:** My research goal is tip analysis for credit card payments in Yellow Taxi used around New York by also incorporating weather data.

**Timeline:** The timeline for the research area is December 2023 - May 2024.

To run the pipeline, please visit the `notebooks` directory and run the files in order:
1. `download.py`: This downloads the raw data into the `data/raw` directory as github does not like large files.
2. `PreProcessing.ipynb`: This notebook details all preprocessing steps and outputs it to the `data/raw`directory. It mostly just converts data types.
3. `DataCleaning.ipynb`: This notebook is used to clean the data and make sure everything is good to go before further analysis.
4. `Visualizations.ipynb`: This notebook is for generating some useful plots to explain tipping behaviour based on different parameters such as weather, pick up location, time and day.
5. `Modeling.ipynb`: This is where the modeling is done, also generates some plots such as feature weighting.