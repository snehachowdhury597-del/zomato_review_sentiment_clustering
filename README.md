# Zomato Review Sentiment and Restaurant Clustering Analysis
This project analyzes Zomato restaurant reviews to understand customer sentiment and identify patterns in ratings and customer behavior. The goal is to extract meaningful insights from review data and group restaurants into different segments using machine learning techniques.

## Problem Statement

Online food delivery platforms like Zomato generate a large amount of customer reviews and ratings.
Analyzing this data can help understand customer satisfaction and restaurant performance. 
This project uses sentiment analysis and clustering techniques to analyze customer opinions
and group restaurants based on similar characteristics.

## Dataset

The project uses Zomato restaurant review datasets containing information such as:

* Restaurant name
* Customer reviews
* Ratings
* Cost
* Number of pictures
* Cuisine types
* Reviewer activity

## Project Workflow

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Sentiment Analysis on Customer Reviews
4. Feature Engineering
5. Hypothesis Testing
6. Unsupervised Learning (Clustering)
7. Model Evaluation using Silhouette Score

## Machine Learning Techniques Used

* TF-IDF Vectorization for text features
* Sentiment Analysis
* K-Means Clustering
* Hierarchical Clustering
* DBSCAN Clustering

## Evaluation Metric

Silhouette Score was used to evaluate clustering performance and identify the best clustering model.

## Key Insights

* Experienced reviewers tend to rate restaurants differently.
* Reviews with pictures often receive higher ratings.
* Cost and rating show a weak positive relationship.
* Restaurants can be segmented into different groups based on review behavior and features.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* NLTK
* Scipy

## Conclusion

This project demonstrates how machine learning can be used to analyze large volumes of restaurant review data to extract customer insights and group restaurants into meaningful segments for business decision-making.
