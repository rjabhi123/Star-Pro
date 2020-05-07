# Udacity-Starbucks-Capstone-Pro
This repository has all the code and report for my Udacity Data Scientist Nanodegree Capstone project.

# Installations
This project was written in Python, using Jupyter Notebook on Anaconda. The relevant Python packages for this project are as follows:

   * pandas
   * numpy
   * math
   * json
   * matplotlib
   * seaborn
   * from sklearn.model_selection import train_test_split, GridSearchCV
   * from sklearn.linear_model import LogisticRegression
   * from sklearn.neighbors import KNeighborsClassifier
   * from sklearn.tree import DecisionTreeClassifier
   * from sklearn.svm import SVC
   * from sklearn.ensemble import RandomForestRegressor
   * from sklearn.naive_bayes import GaussianNB 
   
  
# Project Motivation
This project is the Capstone project of my Data Scientist nanodegree with Udacity. As students in the nanodegree, we have the option to take part in the Starbucks Capstone Challenge. For the challenge, Udacity provided simulated data that mimics customer behavior on the Starbucks rewards mobile app.The objective is to try to find how Starbucks customers use the app, and how well is the current offers system. more importantly, to find patterns and show when and where to give specific offer to a specific customer.
  
# File Descriptions

1. The data used in the project is in the files : 
     * portfolio.json :-  containing offer ids and meta data about each offer (duration, type, etc.).
     * profile.json :- demographic data for each customer.
     * and transcript.json :- records for transactions, offers received, offers viewed, and offers completed.
     
2. Starbucks_Capstone_notebook.ipynb :- contains all the work.


# implementation

This dataset contains simulated data that mimics customer behavior on the Starbucks rewarding system in their mobile application. Once every few days, Starbucks sends out an offer to users of the mobile app. The message can be an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. We are going to analyze three file:
  * portfolio
  * profile
  * transcript
  
The process of our analysis will be by the following step: Define our Business question, understanding the Datasets, Data preparation and wrangling, analyze the data, model the data, compare model performance, and finally selecting one model and improving it.
   * Business Understanding :-  The objective here is to find patterns and show when and where to give specific offer to a specific   customer.
   * Data Understanding :- Let’s see table by table so we can have an overview.
   * Data preparation and wrangling :- Based on what we have seen in the previous step, there needs to be some work to prepare the data for analysis and modeling.
   * Analyzing the Data : - For this part, it will be divided into Univariate Exploration and Multivariate Exploration.
      1. Univariate Exploration :- First, let’s start with the Univariate Exploration and try to answer the following questions:
          i)   What is the average income for Starbucks customers?
          ii)  What is the average age for Starbucks customers?
          iii) What is the most common promotion?
          iv) What are the most common age group and gender?
          v)  Who are the most loyal customer (most transcripts)?
          

 
# Results
The main results of the code can be found at the post available [here](https://medium.com/@rabhimanyu509/starbucks-project-9ca045b6a66c).
  
# Acknowledgements
I want to thank the Udacity Data Science Nano-Degree Program for giving me this opportunity to do the project.

  
