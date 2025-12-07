Iris Flower Classification (Machine Learning Project):

This project builds a machine learning classifier that predicts the species of Iris flowers using the classic Iris dataset. It includes data exploration, visualization, preprocessing, and training two popular classification algorithms: K-Nearest Neighbors (KNN) and Logistic Regression. This is an excellent beginner-friendly ML project demonstrating the full workflow of a supervised classification problem.

Project Overview:
The Iris dataset contains measurements of various flower parts, including
Sepal length
Sepal width
Petal length
Petal width
Using these features, the model predicts one of the three species:
Setosa, Versicolor, Virginica

Tech Stack:
Python
Pandas, NumPy
Seaborn, Matplotlib
Scikit-learn

Key Steps in the Project
1️) Data Loading
Load the Iris dataset using Scikit-learn and convert it into a Pandas dataframe with labeled species names.

2️) Explorator Data Analysis (EDA)
Visualize relationships using pairplots
Analyze feature correlations using a heatmap
Study feature distributions using histograms
These visualizations help understand how features separate different flower species.

3️) Data Preprocessing
Split the data into training and testing sets, then standardize features using StandardScaler, which improves KNN and Logistic Regression performance.

4️) Model Training
Train two classification models:
K-Nearest Neighbors (KNN)
Logistic Regression

5️) Model Evaluation
Evaluate models using:
Accuracy Score
Confusion Matrix
Heatmap visualization for the confusion matrix
These metrics clearly show how well each model performs.
