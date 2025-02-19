# Introduction
Analyzing Amazon dataset to optimize product recommendation systems and provide other suggestions to boost sales

# Dataset
The data is from crowdsourced survey results regarding Amazon purchases between 2018 to 2022. There are 2 datasets, survey.csv and purchases.csv

## survey.csv
The data contains demographic data for each survey respondent, including race, gender and location based.

## purchases.csv
The data contains information about items purchased, quantity, price, date purchased etc.

# Product Recommendation System
The model is developed using unsupervised learning method of market basket analysis. The model learns from products commonly bought together and in turn will recommend users to purchase products that complement what they have in their shopping cart. This is an item-based recommendation system as we look at the purchase history of different items relative to one another. 

# Future Works
Research shows that user based recommendation systems may work better than system based recommendation systems (Lin, 2014). Combining user segmentation obtained via clustering with the present product recommendation system could then further increase the effectiveness of recommendations given to customers. In turn, this will be expected to increases sales and boost customer satisfaction. 

# Citations
1. Lin, Z. (2014). An empirical investigation of user and system recommendations in e-commerce. Decision Support Systems, 68, 111–124. https://doi.org/10.1016/j.dss.2014.10.003 
