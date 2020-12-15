# MLB_Statcast_Project
Using publicly available Statcast data to do a data analysis on the 2019 MLB season. This is a problem that attempts to build a machine learning model that will classify either a hit or an out. Data was obtained through the [baseball savant search feature](baseballsavant.mlb.com/statcast_search), and instructions on how to download the CSV file from the site can be found in the "Data" folder. 

This classification problem consists of two parts:

1. Using various subsets (2-feature, whole dataset, and 6-feature) of Statcast data for the 2019 Baltimore Orioles season to build various classifiers and test them through various metrics (precision, recall, F1 score, overall accuracy).
2. Taking the best-performing models for each subset, test them on another team (Chicago Cubs) to see how well the models' results generalize.


## Table of Contents

- [Statcast_Data_Cleaning.ipynb](https://github.com/skbetz54/MLB_Statcast_Project/blob/main/Statcast_Data_Cleaning.ipynb) - Google Colab notebook detailing the data cleaning process I went through to get the dataset ready for input into my models

- [Statcast_EDA.ipynb](https://github.com/skbetz54/MLB_Statcast_Project/blob/main/Statcast_EDA.ipynb) - Google Colab notebook that includes several visualizations of the dataset.

- [HowToDownload](https://github.com/skbetz54/MLB_Statcast_Project/blob/main/HowToDownload) - Instructions on how to download baseball player/team data I used in CSV file from baseballsavant.com.

- [Data folder](https://github.com/skbetz54/MLB_Statcast_Project/tree/main/Data) - Folder containing the csv files (cleaned and uncleaned) used in the model creation.


