# Recommendations_with_IBM

## Introduction
For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations to them about new articles they may like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

![screenshot](readme.png)

Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

This project is divided into the following tasks

### I. Exploratory Data Analysis

Before making recommendations of any kind, I explored the data used in the project. There are some basic, required questions to be answered about the data which is used throughout the rest of the notebook. 

### II. Rank Based Recommendations

Find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

### IV. Content Based Recommendations (in progress...)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using NLP skills and so on to come up with some creative ways to develop a content based recommendation system.

### V. Matrix Factorization

Using the user-item interactions to build out a matrix decomposition. Using the decomposition to get an idea of how well it can predict new articles an individual might interact with (spoiler alert - it isn't great). I will discuss which methods I might use moving forward.
