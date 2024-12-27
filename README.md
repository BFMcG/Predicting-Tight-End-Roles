# Predicting-Tight-End-Roles

This Project is based on 2025 data bowl kaggle data set

Before running any files, go to this website and download every file: https://www.kaggle.com/competitions/nfl-big-data-bowl-2025/data

My Competition Submission:

## Files
File Order (1 - 5)

### Data Merging.Rmd
1) Start with this file, which merges all of the data sets together and prepares them for further cleaning

### Data Cleaning.Rmd
2) Run this file after Data Merge.Rmd, this file cleans all of the data and merges it into one concise data set used for model creation.

### Models.Rmd
3) Run this file after Data Cleaning.Rmd

Fitting data to Random Forest models, comparing ran models, and creating model visualizations
   
### EDA.Rmd
4) Exploratory Data Analysis, isn't a required data set to run Models.Rmd

only requires Data Merge and Data Cleaning to be run first. 

Analyzes the significance of parameters being considered for model creation.

### Model Testing.Rmd
5) Isn't required to run Models.Rmd

only requires Data Merge and Data Cleaning to be run first

Testing the cleaned data on several models including Logistic Regression, Elastic Net Regression, Support Vector Machine, Gradient Boosted Tree, and Random Forest
