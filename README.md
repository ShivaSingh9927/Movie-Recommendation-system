# Movie-Recommendation-system
Creating a Movie Recommendation System by implementing Model-Based Collaborative Filtering by using singular value decomposition (SVD) and Memory-Based Colllabroative Filtering by computing cosine similarity. 
Two most common types of recommender systems are Content-Based and Collaborative Filtering (CF).

Collaborative filtering produces recommendations based on the knowledge of users’ attitude to items, that is it uses the "wisdom of the crowd" to recommend items.
Content-based recommender systems focus on the attributes of the items and give you recommendations based on the similarity between them.

#Collaborative Filtering
In general, Collaborative filtering (CF) is more commonly used than content-based systems because it usually gives better results and is relatively easy to understand (from an overall implementation perspective). The algorithm has the ability to do feature learning on its own, which means that it can start to learn for itself what features to use.

CF can be divided into Memory-Based Collaborative Filtering and Model-Based Collaborative filtering.

The Data
We will use famous MovieLens dataset, which is one of the most common datasets used when implementing and testing recommender engines. It contains 100k movie ratings from 943 users and a selection of 1682 movies.
