# NETFLIX_EDA_ML

This project involves an in-depth analysis of the Netflix titles dataset, followed by the development of a machine learning model to classify titles into Movies and TV Shows. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, and model development using Python and its libraries in Google Colab.

##Overview

The primary objective of this project is to analyze Netflix titles and build a predictive model to classify whether a given title is a movie or a TV show. The analysis includes understanding trends, distributions, and relationships in the dataset. The machine learning model is trained using the Gradient Boosting Classifier.

##Dataset
The dataset used in this project is netflix_titles.csv, which contains information about Netflix titles, including their type, title, director, cast, country, date added, release year, rating, duration, and listed genres.

##Project Steps
Step 1: Exploratory Data Analysis (EDA)
Load and inspect the dataset.
Check for missing values and visualize them.
Analyze the distribution of titles by type, rating, release year, and year added.
Visualize top genres.

Step 2: Data Preprocessing
Handle missing values.
Convert date_added to datetime format and extract year and month.
Encode categorical variables (rating and listed_in).
Prepare features and target variable for the model.

Step 3: Machine Learning Model
Split the data into training and testing sets.
Train a Gradient Boosting Classifier.
Evaluate the model using cross-validation and test set metrics.

Step 4: Model Evaluation
Calculate accuracy score.
Generate a classification report (precision, recall, F1-score).
Plot the confusion matrix.

#Results
The results section includes visualizations to help interpret the findings:

Confusion Matrix Heatmap: To visualize model performance.

Distribution Plots: For titles by release year and year added.

Top Genres: Bar plot of the most common genres on Netflix.
