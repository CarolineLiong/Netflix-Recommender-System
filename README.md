# Netflix-Recommender-System
![alt text](https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg)

Project based on the Netflix Prize: Given training data of 200 users and their ratings of a possible 1000 movies, predict what others users would rate would rate particular movies.

Methods for prediction include: User-Based Collaborative filtering using cosine similarity w/ k-nearest neighbors, pearson correlation, pearson correlation with IUF (Inverse User Frequency) and case amplification modifications, and item-based collaborative filtering using adjusted cosine similarity.


Custom methods of prediction include just taking the average of the user's previous ratings of the user and using that average as the predicted ratings (which worked surprisingly well) and predicting using the average predicted ratings from the cosine, pearson, and item-based algorithms. The latter ended up performing the best with an MAE of 0.758. 

