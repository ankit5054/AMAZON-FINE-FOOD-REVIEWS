# AMAZON-FINE-FOOD-REVIEWS

![download](https://user-images.githubusercontent.com/39160589/59823264-50446280-934b-11e9-83a8-5fb038b997eb.png)

# ABOUT DATA
## Context
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

## Contents
Reviews.csv: Pulled from the corresponding SQLite table named Reviews in database.sqlite
database.sqlite: Contains the table 'Reviews'

Data includes:
- Reviews from Oct 1999 - Oct 2012
- 568,454 reviews
- 256,059 users
- 74,258 products
- 260 users with > 50 reviews

## ATTRIBUTES / FEATURES
- Id
- ProductId - unique identifier for the product
- UserId - unqiue identifier for the user
- ProfileName
- HelpfulnessNumerator - number of users who found the review helpful
- HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
- Score - rating between 1 and 5
- Time - timestamp for the review
- Summary - brief summary of the review
- Text - text of the review

## OBJECTIVES
![download1](https://user-images.githubusercontent.com/39160589/59823825-0ceaf380-934d-11e9-99c0-40a27b450c49.jpg)
 ### SENTIMENTAL ANALYSIS 
 To predict whether the given review is positive or negative .i.e., 1 or 0
## FEATURIZATION
In this we are applying the techniques like 
- BAG OF WORDS(BOW)
- Term Frequency–Inverse Document Frequency(TF-IDF)
- WORD2VEC (W2V)
- TF-IDF WORD2VEC(TFIDF W2V)

## ALGORITHMS APPLIED TO PREDICT.

### - KNN
### - Naive Bayes
### - Logistic Regression
### - Support Vector Machine
### - Decision Tree
### - XGBoost and RandomForest
### - K-means, Agglomerative, DBSCAN Clustering
### - Truncated SVD
