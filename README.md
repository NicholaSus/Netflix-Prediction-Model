# Netflix Content Analysis and Type Prediction

## Project Overview
This project analyzes Netflix content data and builds machine learning models to predict content types. It includes exploratory data analysis, visualization, and the implementation of various classification algorithms.

## Table of Contents
1. [Data Preprocessing](#data-preprocessing)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
3. [Visualization](#visualization)
4. [Machine Learning Models](#machine-learning-models)
5. [Requirements](#requirements)
6. [Usage](#usage)

## Data Preprocessing
- Load Netflix data from 'netflix_titles.csv'
- Clean rating data by replacing specific durations with 'No Data'
- Remove rows with missing values in 'country', 'rating', and 'listed_in' columns

## Exploratory Data Analysis
- Analyze country distribution of Netflix content
- Examine release year trends for movies and TV shows
- Investigate age ratings for movies and TV shows

## Visualization
- Create countplots for top countries producing Netflix content
- Generate line plots for content type trends over years
- Produce horizontal bar charts for age ratings
- Visualize country and rating relationships

## Machine Learning Models
Three classification models are implemented to predict content type:

1. Random Forest Classifier
2. Decision Tree Classifier
3. AdaBoost Classifier

Each model undergoes hyperparameter tuning using RandomizedSearchCV and is evaluated using confusion matrices.

## Requirements
- numpy
- pandas
- seaborn
- matplotlib
- plotly
- scikit-learn
- yellowbrick

## Usage
1. Ensure all required libraries are installed.
2. Place the 'netflix_titles.csv' file in the same directory as the script.
3. Run the script to perform analysis and train models.
4. View the generated visualizations and model performance metrics.