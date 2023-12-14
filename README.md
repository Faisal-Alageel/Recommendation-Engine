# Recommendation-Engine

## a Recommendation Engine using Machine Learning & Statistical Analysis
The recommendation engine is designed to provide personalized recommendations based on user preferences, It utilizes machine learning algorithms such as collaborative filtering techniques to identify patterns and similarities among users' behavior.
Additionally, a statistical analysis technique is employed to provide recommendations based on product ratings and the number of ratings.

## Overview
The ML based recommendation engine is constructed using the Surprise framework, incorporating the Singular Value Decomposition (SVD) Algorithm for generating user-product recommendations. 
SVD is a matrix factorization technique that decomposes the user-item interaction matrix into user and item latent factors.

For the statistical analysis approach, I've applied the IMDB formula for rating based recommendations. 

## Results 
The model performance on the recommended items is as follows:  
### On the training set:  
**Precision**: 92%  
**Recall**: 100%  
**F1-score**: 96%     
### On the testing set:  
**Precision**: 86%  
**Recall**: 99%  
**F1-score**: 92%  

## Dataset

the dataset used is the [Amazon product reviews](https://www.kaggle.com/datasets/saurav9786/amazon-product-reviews/) , 

which contains (user id, product id, product rating, timestamp)

## Instructions

1. to clone this repo with the data, you need to run ` git lfs clone https://github.com/Faisal-Alageel/Recommendation-Engine.git `
2. Install the required dependencies, I suggest installing pandas, numpy, matplotlib, and surprise.
   for that I suggest using Conda package manager, creating your `Python 3.11` environment and installing surprise by runnning `conda install -c conda-forge scikit-surprise`
3. Run & explore `Recommendations.ipynb`  :) 
