**General Info:**

A recommendation engine is a class of machine learning which offers relevant suggestions to the customer. It recommend the products which are currently trending or highly rated and they can also recommend the products which bring maximum profit to the company.
Types Of Recommendation System
A recommendation system is usually built using 3 techniques which are content-based filtering, collaborative filtering, and a combination of both.

1) Content-Based Filtering
The algorithm recommends a product that is similar to those which used as watched. In simple words, In this algorithm, we try to find finding item look alike.
Only it recommends the product which has the highest score based on past preferences.

2) Collaborative-based Filtering
Collaborative based filtering recommender systems are based on past interactions of users and target items.  In simple words here, we try to search for the look-alike customers and offer products based on what his or her lookalike has chosen. 

3) Hybrid Filtering Method
It is basically a combination of both the above methods. It is a too complex model which recommends product based on your history as well based on similar users like.

**Overview:**

A book recommendation system is a type of recommendation system where we have to recommend similar books to the reader based on their interest. The books recommendation system is used by online websites which provide ebooks like google play books, open library, good read’s, etc.

A Collaborative based filtering method is used to build a book recommender system.

**Dataset Description:**

There are 3 files in our dataset extracted from some books selling website.

Books - The first file contains all the information related to books like an author,book title,publication year,ISBN,etc.
Users - The second file contains registered user's information like user id,location.
Ratings - Ratings file contain information like which user has given how much rating to which book.
Based on this 3 files a powerful collaborative filtering model is build.

A large dataset consists of 271360 books data and total registered users on the website are approximately 278000 with 11 lakh ratings.
The values in the CSV file are separated by semicolons and not by comma.

**Exploratory Data Analysis:**

1. Extract users and ratings who have given more than 200 ratings.
2. Extract books that have received more than 50 ratings.
3. Create Pivot Table

**Modeling:**

The dataset obtained after exploratory data analysis is used for clustering based on euclidian distance with the nearest neighbors KNN algorithm.
It gives us all the 10 suggested books to the input book.
Hence,a reliable book recommendation system is build to an end-to-end project.
