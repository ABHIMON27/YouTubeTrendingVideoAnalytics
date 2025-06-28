# Youtube Trending Video Data Analysis

# Data Description:
This dataset includes several months (and counting) of data on daily trending YouTube videos. 

The data also includes a category_id field, which varies between regions. To retrieve the categories for a specific video, find it in the associated JSON. One such file is included for each of the five regions in the dataset.

# Tasks performed:
Performing analysis and predictions on YouTube video dataset.
- Task 1: Clean and standardize YouTube trending datasets from different countries
- Task 2: Use SQL to rank categories by avg views
- Task 3: Perform sentiment analysis on titles and tags

# Algorithms used:
# Task 1: Clean and standardize YouTube trending datasets from different countries
      Data is included for the US, CA, RU, JP and IN regions (USA, Canada, Russia, Japan and India respectively), with up to 200 listed trending videos per day.

Each region’s data is in a separate file. Data includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count.
      - Multinomial NB
      - Support Vector Classifier
      - Random Forest Classifier
      - K Neighbors Classifier
      - Decision Tree Classifier
# Task 2: Use SQL to rank categories by avg views
      - Linear Regression
      - Random Forest Regressor
      - Gradient Boosting regressor
      - Ridge Regression
      - ElasticNet
# Task 3: Perform sentiment analysis on titles and tags
      - TextBlob
      - Support Vector Machine (SVM)
      - Logistic Regression
   Note:
     As there was no seperate feature for sentiment, in the initial step, textblob was used to perform sentiment analysis on the description, tags and titles separately and a new column called sentiment was attached to the dataframe. After that, SVM and Logistic Regression were applied on the dataframe for performance evaluation. So here, the accuracy for SVM and LR are based on their performance with respect to textblob.

# Instructions to run:
You will require Jupyter Notebook or any Python IDE with Python 3.0 to run the code.

# References
- Dataset Source: https://www.kaggle.com/datasnaek/youtube-new