# Udacity_Data_Scientist_P3

# Starbucks Capstone Project:
Repository for the final Udacity Data Scientist NanoDegree Project.

# Project Outline:

This dataset comprises simulated data emulating customer interactions within the Starbucks Rewards mobile app. Periodically, Starbucks dispatches offers to mobile app users, which can range from promotional advertisements for beverages to tangible offers like discounts or BOGO (buy one get one free) deals. Certain users may not receive any offers in specific weeks. The diversity of offers distributed among users presented a challenge addressed in this dataset. 
The objective is to integrate transaction, demographic, and offer information to discern which demographic segments exhibit optimal responses to specific offer types.
It's important to note that this dataset represents a simplified rendition of the actual Starbucks app, as the underlying simulator features only one product, while Starbucks, in reality, offers a wide array of products.

The goal of the project is, after understanding the data properly, to obtain a model that can predict whether an offer is completed or not, based on some of the demographics and offer properties.


# Modules Used:

For the Data analysis and development of this project, these were the main libraries used:

Data Processing and Visualization:
  - pandas 
  - numpy 
  - math
  - json
  - seaborn 
  - matplotlib.pyplot
    
Modelling:

  - sklearn.preprocessing  (StandardScaler, OneHotEncoder)
  - sklearn.ensemble (RandomForestClassifier)
  - sklearn.model_selection (train_test_split)
  - sklearn.metrics  (classification_report, accuracy_score)

# Files:
The repository contains a Files directory which has the following datasets:
portfolio.json
profile.json
transcript.json (I could not upload it due to Git size restrictions)


# Links:
Jupyter notebook used:
https://github.com/OvaloPicatecla/Udacity_Data_Scientist_P3/blob/main/Starbucks_Capstone_notebook.ipynb
Summary Write-Up for the project:
https://github.com/OvaloPicatecla/Udacity_Data_Scientist_P3/blob/main/StarBucks%20Capstone%20Project.pdf

