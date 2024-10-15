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
7. Conclusion

1. Project Setup
  To run this project on your local machine, ensure you have the following libraries installed:

   pandas
   numpy
   matplotlib
   seaborn
   sklearn
   
   You can install the required libraries using pip:
       pip install pandas numpy matplotlib seaborn scikit-learn

2. Data Handling and Error Management
 In this project, the diabetes.csv file is loaded using pandas. If the file if loaded successful the message will print 'File Successfully loaded'. To handle potential file-related issues (e.g., the file not being found), error handling is implemented using the in-built - 'Try and Except' Error handling method. 
 
3. Exploratory Data Analysis (EDA)
 
In this project, time is taken to understand the data itself through the following:

(i) Checking Data Types: Knowing the data types for each column to ensure appropriate processing.
(ii) Descriptive Statistics: Calculating key summary statistics (mean, median, standard deviation, etc.).
(iii) Distribution of Target Variable: Visualizing the distribution of the diabetes outcome using pie-chart plot.

4. Data Cleaning
Data used from Kaggle, after exploration it is seen as noisy, need for removing unneccessary data befor analysing or modelling. I have used functions for clarity, usability and in the following :
(i) 
