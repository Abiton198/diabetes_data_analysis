# Project Overview
Solo project for data handling. 
A dataset from Kaggle (https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset) has been used. 
The dataset used for this project contains various attributes related to diabetes patients, such as glucose levels, blood pressure, insulin levels, and body mass index (BMI), along with the target variable indicating diabetes status.

# Motivation
To show the data handling skills such as reading files, cleaning, manipulation, analysis and visualization using the Python language in the Jupyter lab.

# Table of Contents

1. Project Setup
2. Data Handling and Error Management
3. Exploratory Data Analysis (EDA)
4. Data Cleaning
5. Feature Engineering
6. Data Visualization
7. Usage
8. Conclusion




# Project Setup
  To run this project on your local machine, ensure you have the following libraries installed:

   pandas
   numpy
   matplotlib
   seaborn
   sklearn
   
   You can install the required libraries using pip:
       pip install pandas numpy matplotlib seaborn scikit-learn

# Data Handling and Error Management

In this project, the diabetes.csv file is loaded using pandas. If the file if loaded successful the message will print 'File Successfully loaded'. To handle potential file-related issues (e.g., the file not being found), error handling is implemented using the in-built - 'Try and Except' Error handling method. 
 
# Exploratory Data Analysis (EDA)
 
In this project, time is taken to understand the data itself through the following:

(i) Checking Data Types: Knowing the data types for each column to ensure appropriate processing.
(ii) Descriptive Statistics: Calculating key summary statistics (mean, median, standard deviation, etc.).
(iii) Distribution of Target Variable: Visualizing the distribution of the diabetes outcome using pie-chart plot.

# Data Cleaning

Data used from Kaggle, after exploration process it is seen as noisy,and the need for removing, renaming, and dropping some unneccessary data before analysing further or use it for modelling in machine learning projects. I have used functions for clarity, code re-usability and scalability in the following :

(i) Handling Missing Values: Missing values can affect the quality of analysis, and even affect the quality of a model. All missing values in this instance are handled and checked.
(ii) Handling Duplicates: The data was checked for any duplicates so that data will not give any bias outcome.

# Feature Engeneering

# Usage

Load Data: Use pd.read_csv() to load the dataset.
Clean Data: Use the handle_missing_values() function to address missing data.
Feature Engineering: Categorize columns such as Patient_Age using categorize_age().
Visualize Data: Create histograms or pie charts for insights.