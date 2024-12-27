# Predicting-Tight-End-Roles

This project is an entry for the 2025 data bowl. It uses a Kaggle data set to train models that can predict what a tight ends role/assignment will be post-snap given pre-snap data.

Link to download csv files: https://www.kaggle.com/competitions/nfl-big-data-bowl-2025/data

My Submission:

## Files
File Order (1 - 5)

### Data Merging.Rmd
1) Start with this file, make sure you've downloaded every file from Kaggle beforehand. This Rmd merges all of the data sets together and prepares them for further cleaning

### Data Cleaning.Rmd
2) Run this file after Data Merge.Rmd, this file cleans all of the data and merges it into one concise data set used for model creation.

### Models.Rmd
3) Run this file after Data Cleaning.Rmd, the file includes fitting data to Random Forest models, comparing ran models, and creating model visualizations
   
### EDA.Rmd
4) Exploratory Data Analysis, only requires that Data Merge.Rmd and Data Cleaning.Rmd are run first. Analyzes the significance of parameters being considered for model training.

### Model Testing.Rmd
5) This Rmd only requires that Data Merge and Data Cleaning are run first. In this file, the cleaned data is being trained on several models including Logistic Regression, Elastic Net Regression, Support Vector Machine, Gradient Boosted Tree, and Random Forest
