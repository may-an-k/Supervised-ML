# Hotel Recommendation system using a supervised learning approach

## Description
This project represents a machine-learning and statistical inferencing approach to determine how a new customer should anticipate their visit based on reviews left by previous customers. 

## Methodology 
### Data Preparation and Exploration

#### Data Acquisition:
The dataset was acquired from Kaggle (https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe/data) and it contains reviews left by  515,000 customer reviews of 1493 luxury hotels across Europe.

#### EDA
Performed data cleaning and initial EDA to get relevant features to conduct downstream analysis 

#### Sentiment Analysis
- Since text data is primarily unstructured data, I used a sentiment analysis approach to map lexical features to sentiment scores to enable better prediction
- VADER sentiment analysis from the NLTK package was used for feature engineering

#### Model Development
- Tree-based models were chosen for the final evaluation as they are capable of capturing complex relationships and determining feature importance. This was crucial to perform factor analysis. 
- Dataset is large enough to use a non-parametric modeling approach
- Models used: Decision tree, Random Forest and Adaboost

#### Factor Analysis
Using factor analysis to provide additional scoring categories to improve the recommendation algorithm 

#### Hotel Recommender
- Building a hotel recommender based on the data generated from the factor analysis
- Generates hotel recommendations based on customer preferences

  



