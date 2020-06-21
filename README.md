# Movie Recommendation System

## Movie Recommendation System with Cosine Similiarty

### Recommendation System works with 3 techniques
1. Content Based  Filtering - Works with type of movie like action, adventure, comedy etc (genres) irrespective of user rating (behaviour)
2. Collaborative Filtering - Works with user rating of the movie (cosine similarity between the movies)
3. Hibrid Filtering - Uses both content and collaborative filtering technique

![alt text](/cosine_similarity.png)

### Cosine similarity:
Cosine similarity is a measure of similarity between two non-zero vectors of an inner product space. It is defined to equal the cosine of the angle between them, which is also the same as the inner product of the same vectors normalized to both have length 1.


## Life cycle of Data Science Project

1. Data Gathering - ( example: collect data from Kaggel )
2. Data Analysis - ( Analyze the data and find the relationship among the tables )
3. Feature Engineering - ( Fix missing values, Temporal, Categorical variables, Standardization, Normalization ) 
4. Feature Selection - ( Extract features which are necessary and imporve the perfomance respect to output )
5. Model building - ( creat a model which suites to our requirements )
6. Train the model
7. Save the model as pickle file - (.pkl)
8. Create a web application with Flask Microservices Framework
9. Read the pickle file in the python flask file and predict the output of model
10. Deploy the webapplication and model in the could servers


#### Build Movie Recommendation System with  below data sets

We have built recommendation system for Hollywood movies from 2013 to 2018. 

DataSource :  https://grouplens.org/datasets/movielens/latest/

Details: http://files.grouplens.org/datasets/movielens/ml-latest-README.html

It contains 27753444 ratings and 1108997 tag applications across 58098 movies. 
These data were created by 283228 users between January 09, 1995 and September 26, 2018. 
This dataset was generated on September 26, 2018. 
movies.csv , ratings.csv, tags.csv, links.csv ,genome-scores.csv ,genome-tags.csv

During deployment of this model in to heroko seeing problem due to huge size of modle and trained vector
model size give approxmatly 200MB. This much huge data not accepted in github during commt time also
we are going to reduce this dataset size and number of year of movies

Collect data from 2013 to till 2018 - 10 yrs movies 
instead of 20 years data we taking 10yrs data

From the above Life cycle of  Datascience project, Steps 1 to 7 are implemented in MRSHollywood_Develpment project. Steps 8 to 10 are implemented in MRSHollywood_Deployment.


Implemented Android app for this movie recommendation system ie MRSHollywood_Android.

Implemented Google Dailogflow Live Chat which helps to find and suggest best movies to users ie MRSHollywood_LiveChat.

### Usefull Links
[MRSHollywood_Deployment](https://github.com/nrkreddy94/MRSHollywood_Deployment)

[MRSHollywood_Android](https://github.com/nrkreddy94/MRSHollywood_Android )

[MRSHollywood_LiveChat](https://github.com/nrkreddy94/MRSHollywood_LiveChat)



