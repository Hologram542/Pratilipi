# Recommending Praatilipi

### In this jupyter notebook I used two recommendation methods
### 1. Popularity based Recommendation system
### 2. Collaborative Filtering Based Recommender System

## Popularity based Recommendation system
### This is one of the most used type of recommendation systems used. 
### Since it recommends the most popular contents on the Database based on a metric (be it existing or custom) the changes of users liking them is high.

## Collaborative Filtering Based Recommender System
### Another type of recommendation system which draws relationships between two parameters (in this case "user_id" and "pratilipi_id") and plots them on a 2D plane.
### When it's time to recommend something, we take the closest points to our data point in the 2D plane and recommend that to our user.

# How do we improve these models ? 
### The most efficient way to improve our model in this case is to build a more sophisticated metric to define the popularity of these stories.
### Another possible solution is to collect more relevant data.

# Any Alternatives ? 
### There are definitely other things we could try, like using a different type of recommendation system.
### There is a recommendation system called Content based filtering which takes the user's past actions and recommends what the user might like.
### There is also Hybrid Recommendation system which is basically a combination of Content based and Collaborative based filtering.
