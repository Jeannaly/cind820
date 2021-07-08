# cind820
In this project I aim to develop machine learning algorithms, that will present users with recommendations on which movies they might enjoy. These algorithms are known as recommender systems.

A recommender system finds the similarities between the items and or users in a dataset, and predicts or recommends new items for the users’ consumption. To develop said recommender systems I’ve applied two main techniques. 

•	The Market Basket Analysis, is used to identify item subsets, based on purchase frequency. Using the data-mining algorithm, Apriori, we can identify which movies users tend to watch together. 
o	This will allow us to make instant recommendations for users that have not yet rated movies, and have watched at least one movie. 

•	Content- Based Recommender System, using the similarity/dissimilarity coefficient between user’s genre preferences and movie genres. 
o	This will result in a list of the top N recommended movies that best match the user’s preferences. I will be testing three distance measures to achieve this recommendation: simple matching, Jaccard and Dice.

To train the models, I’ve chosen the small MovieLens dataset, which is a subset of the large MovieLens dataset. Specifically, the movies.csv and the ratings.csv data. This dataset contains 100,0836 ratings applied to 9742 movies, by 610 users. Each movie is identified by a unique movie ID, it’s title alongside its release year, and the genres to which the movie belongs. And each rating contains the user ID, the movie ID and the 5-star rating. 

All users featured in this data subset were selected at random, and had rated at least 20 movies. The data was created between March 29, 1996 and September 24, 2018.
