# User_based_collaborative_filtering__recommendation_engine
## Instalation
Anaconda environment
Jupyter notebood
Python 3.6
## Motivation
We provide a Recommendation engine based on collaborative filtering by adopting three main steps :

1. Remove items already consumed by users.
2. Find reviewed items (interaction metric) from user neighbors that highly correlate in terms of rating
3. Recommend the filtered items to each other user where both 1 and 2 above hold

We implement the three-step process above to make recommendations for every users in the real time movie tweetings dataset. We go through the process of providing recommendations for individual pairs of users, then latter on extend via looping to all users.
The suitable evaluation metric for this project would be through online AB Testing


![alt text](https://github.com/Tsakunelson/User_based_collaborative_filtering_recommendation_engine/blob/master/user_based_collab_recs.png)
