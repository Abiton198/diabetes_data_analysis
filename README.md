# Project Overview
Solo project for data handling. 
A dataset from Kaggle (https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset) has been used. 
The dataset used for this project contains various attributes related to diabetes patients, such as glucose levels, blood pressure, insulin levels, and body mass index (BMI), along with the target variable indicating diabetes status  with the goal of identifying patterns in diabetes-related factors.

# Motivation
This project aims to demonstrate data handling, cleaning, manipulation, and visualization skills in Python, particularly when working with healthcare data, which is often noisy and incomplete. The project also showcases the ability to uncover insights that could support future machine learning models for diabetes prediction.

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

In this project, the diabetes.csv file is loaded using pandas. 
    
   with open('diabetes.csv') as df:
        ds = pd.read_csv(df)
        print("File loaded successfully!")
        
To handle potential file-related issues (e.g., the file not being found), error handling is implemented using the in-built - 'Try and Except' Error handling method. 
 
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
The process of creating new features or modifying existing ones in a dataset to improve the performance of machine learning models. It changes raw data into meaningful representations that better capture the underlying patterns and relationships needed for future use. In this prject the following are used:

(i) Binning Continuous Variables: created age groups like young, middle-aged, and senior for further use of data, if the data is to be used for an algorithm it improves learning from a pattern of data thereby enhencing the predictive power of the model.
(ii) Renaming Columns: Renaming columns to more descriptive names to improve readability and communication. Giving a sense of data ownership and understanding.

# Data visualization
The graphical representation of data and information using charts, graphs, maps, and other visual formats. In this project to have an intuitive way to see and understand trends, patterns, and insights in data I used histogram and a pie-chart. This visualization makes complex data easier to comprehend, interpret, and communicate, which is essential for data-driven decision-making.
(i) Compare distribution: To see the distribution of BP_measurement and Body Mass Index provides insights into potential correlations between these health factors, which are critical in diabetes diagnosis and management.
(ii) Pie-chart: a comparison between the two outcomes, useful for conclusive analysis of data. 

# Usage
git clone https://github.com/Abiton198/diabetes_data_analysis this project and run it in Jupyter Lab. Each code cell in the notebook follows a logical sequence, from loading data to visualizing it. Functions are modular to ensure ease of use for various data handling tasks

# Conclusion
In the future, this dataset can be used to train machine learning models like decision trees or logistic regression for diabetes prediction. The data preparation steps undertaken here ensure that the dataset is clean and feature-rich, paving the way for accurate and meaningful model training.