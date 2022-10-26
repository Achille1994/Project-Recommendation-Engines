# Project Recommendation-Engines

Introduction
For this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like. Below we can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.
In order to determine which articles to show to each user, We will be performing a study of the data available on the IBM Watson Studio platform.

<img width="991" alt="Screenshot 2022-10-26 at 09 33 12" src="https://user-images.githubusercontent.com/74813723/197963319-7891754e-078b-41d0-be03-f6afe39cd7ea.png">

### Project motivation

In the IBM Watson Studio, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. Users of the system interact with all of this. Within this scope, we created this recommendation system project to enhance the user experience and connect them with assets. This personalizes the experience for each user.

By following the table of contents, I will build out a number of different methods for making recommendations that can be used for different situations. 
## Table of Contents

I. [Exploratory Data Analysis](#Exploratory-Data-Analysis)<br>
II. [Rank Based Recommendations](#Rank)<br>
III. [User-User Based Collaborative Filtering](#User-User)<br>
IV. [Matrix Factorization](#Matrix-Fact)<br>
V. [Extras & Concluding](#conclusions)

### Tasks
Our project will be divided into the following tasks

I. Exploratory Data Analysis:

Before making recommendations of any kind, we will need to explore the data. Dive in to see what I can find. 

II. Rank Based Recommendations:

To get started in building recommendations, We will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering:

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

IV. Matrix Factorization:

Finally, We will complete a machine learning approach to building recommendations. Using the user-item interactions, We will build out a matrix decomposition. We will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.

IV. Conclusion:

Please see my notebook for more details



