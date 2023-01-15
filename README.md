# Recommendations-with-IBM
This repository includes codebase of Recommendations with IBM project which is a final assignment of Experimental Design and Recommendations class by Udacity provided as a part of Data Science nanodegree

There're 4 blocks in this codebase. Codebase is collected in one jupyter Notebook. Html and Pdf renders of the notebook are also provided

1. Data Exploration
- Explore the data to understand the number of users, articles, and information about the interactions that take place.
2. Create Rank Based Recommendations
-  The two functions should pull the top ids and the top names.
3. Collaborative Filtering
- Create a matrix with users on the rows and articles on the columns. There should be a 1 if a user-article interacted with one another and a zero otherwise.
- Find similar users needed for user-user collaborative filtering model. A function that finds similar users.
- Make recommendations using user-user based collaborative filtering. Functions needed to make recommendations for each user.
- Improve your original method of using collaborative filtering to make recommendations by ranking the collaborative filtering results by users who have the most article interactions first and then by articles with the most interactions.
- Provide recommendations for new users, which will not be able to receive recommendations using our user-user based collaborative filtering method.

4. Matrix Factorization
1. Perform SVD on user-item matrix. Provides U, Sigma, and V-transpose matrices, as well as an explanation of why this technique works in this case.
2. Split the user-item matrix into training and testing segments. Identify the users in the test set that are also in the training.
3. Perform assessment of the predicted vs. the actual values.
4. Results discussion about the results, as well as a method by which you could test how well your recommendation engine is working in practice.
