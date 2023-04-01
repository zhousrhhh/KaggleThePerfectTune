# Kaggle_Competition_The_Perfect_Tune
I used R to construct supervised machine learning models with a dataset of popular songs, to predict Spotify ratings based on auditory features of the songs. 

## Project Description: 
+ This is a [Kaggle](https://www.kaggle.com/competitions/lalasongs22/overview) competition I participated in November 2022. 
+ It provides dataset that describes popular songs based on auditory features, such as loudness, tempo, performer and genre.
+ The goal is to contruct a predictive model using [analysisData.csv](analysisData.csv), and predict the songs' ratings based on the features in [scoringData.csv](scoringData.csv).
+ Model performance will be evaluated based on [RMSE (root mean squared error)](https://en.wikipedia.org/wiki/Root-mean-square_deviation). 

## Data Analysis Process: 
1. Data Exploration
2. Data Tidying
   - Encode Missing Data
   - Data Parsing
   - Data Transformation
3. Feature Selection
   - Variable Inter-set
   - Remove Near Zero Variance
   - Principal Components Analysis
   - Split Data
4. Data Analysis - Modeling
   - Multiple Regression
   - Regression Tree
   - Random Forest
   - Ranger
   - XGBoost
   - gbm
   - Radial SVM
   - Model Tuning
   - Comparison
5. Prediction
