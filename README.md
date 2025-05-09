# News-Recommendation-System

## Description 
This project aims to build a Content-Based News Recommendation System that suggests 
news articles to users based on the similarity between news content and user interests. The 
system builds a user profile from their explicitly stated preferences (e.g., preferred categories, 
topics, or keywords) and recommends articles with similar content using techniques like 
TF-IDF and cosine similarity. 

We will use the MIND (Microsoft News Dataset), a large-scale dataset from Microsoft News 
that includes detailed article metadata such as titles, abstracts, categories, and 
subcategories—ideal for content-based modeling.

## Requirements 
Functional Requirements: 
● Load and preprocess the MIND dataset. 

● Extract meaningful features from article content (e.g., title, abstract) using TF-IDF. 

● Construct a user profile vector based on selected categories, keywords, or preferred 
articles. 
● Compute cosine similarity between the user profile and news articles. 

● Recommend top-N most similar articles to the user. 

Libraries: 
● pandas, numpy 

● scikit-learn (for TF-IDF and similarity computation) 

● NLTK or spaCy (for text preprocessing, optional) 

● matplotlib / seaborn (for optional visualizations) 


### Dataset: Microsoft News Dataset (MIND): 
https://www.kaggle.com/datasets/arashnic/mind-news-dataset/data 


