# Web-Mining-Final-Project

## Goal
Using Kaggle's [Women's E-Commerce Clothing Reviews](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews), the primary objective was to create a recommender system that utilizes sentiment analysis to suggest clothing items that align with the users’ preferences. This involved using the various columns in this dataset, both numerical and textual, to predict the sentiments in the reviews and use those sentiments along with the user ratings to output recommendations to the user.  

## Methods We Used:
1. Usage Mining: Developed a recommendation system that accepts user input and suggests comparable products to users based on the sentiment expressed in the reviews and average rating of reviews.
2. Content Mining: Preprocessed data using natural language processing before using it for sentiment analysis.
3. Predictive Modeling: Checked the machine's accuracy in determining whether the user recommends a product by using classification models, such as Logistic Regression and Decision Tree Modeling.
4. Data Visualization: Used Python’s visualization libraries, such as matplotlib and seaborn, to create plots that represent the original dataset and our analysis.

### Sentiment Analysis: 
 The goal was to extract meaningful insights from the sentiment analysis results to beter understand the sentiments expressed in the women's clothing e-commerce reviews dataset. 

### Recommendation System: 
Creating a recommendation system involved looking at the average ratings left by the reviewers as well as the sentiment from the actual reviews to recommend similar clothing to a user inputted Clothing ID.

### Classification Model:
Using Logistic Regression and Decision Tree modeling on the reviews and the Recommended IND column enabled the model to accurately predict whether a reviewer would recommend the item or not. 

## Conclusion:
There were more positive reviews compared to negative reviews, which was most likely the reason the classification models could more accurately predict positive classes compared to negative classes. Using a dataset that has equal distribution of positive and negative reviews might have enhanced the overall analysis of using sentiment analysis, recommendation system, and classification model and provided us with better insights to how online shoppers review clothing items.
