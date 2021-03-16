# IBM-Recommendation-System
## Description
This project was about analyzing users who viewed articles on the IBM Watson Studio platform, and make recommendations to them on new articles that fit their interests.
It is divided into 4 sections:
1) Exploratory Data Analysis: Perform data visualisation, cleaning and features engineering
2) Rank Based Recommendations: Return the n top articles ordered with most interactions with users as the top
3) User-User Based Collaborative Filtering: Find the most similar users to each use and use these users to return the articles I would recommend to each user.
4) Content Based Recommendations: Based on user-item interaction, use matrix factorization to make article recommendations to the users on the IBM Watson Studio platform

## Installations
This repository is written in Python and the following Python packages are required: pandas, numpy, matplotlib.pyplot, pickle.

## Files descriptions:
user-item-interactions.csv: csv file containing data about user interactions with articles.
articles_community.csv: csv file containinig description about articles available on IBM Watson Studio platform.
project_tests.py : this is to test if the answers I provided to questions asked by Udacity are correct.
Recommendations_with_IBM.ipynb: Jupyter workbook containing codes for this project.
