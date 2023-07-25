# NoSQL_Challenge
Module 12 Challenge

In this project, we were tasked with analyzing food hygiene ratings data for various establishments across the United Kingdom on behalf of the food magazine "Eat Safe, Love." The project involved using MongoDB and Jupyter Notebook to perform data manipulation, updates, and exploratory analysis.

Part 1: Database and Jupyter Notebook Set Up

In the first part, we set up the MongoDB database named "uk_food" and imported the provided data from the "establishments.json" file. We confirmed the successful import, listed the databases and collections in MongoDB, and displayed one document from the "establishments" collection. This was done in the [NoSQL_setup_starter.ipynb](https://github.com/aliciahlavac/NoSQL_Challenge/blob/main/NoSQL_setup_starter.ipynb) file.

Part 2: Update the Database

The magazine editors requested some modifications to the database before conducting further analysis. We added an exciting new halal restaurant called "Penang Flavours" in Greenwich to the database. We retrieved the BusinessTypeID for "Restaurant/Cafe/Canteen" and updated the new restaurant with the appropriate BusinessTypeID. Additionally, we identified and removed any establishments within the Dover Local Authority, as per the magazine's preferences. We also converted number values stored as strings (latitude, longitude, and RatingValue) to decimal and integer numbers, respectively, using the update_many method in MongoDB.

Part 3: Exploratory Analysis

In the final part, in [NoSQL_analysis_starter.ipynb](https://github.com/aliciahlavac/NoSQL_Challenge/blob/main/NoSQL_analysis_starter.ipynb), we performed exploratory analysis to answer specific questions for "Eat Safe, Love." We used various MongoDB queries and aggregation methods to find relevant insights from the data. We explored hygiene scores, ratings, and other factors to help the magazine's journalists and food critics decide where to focus future articles.

The analysis covered establishments with hygiene scores equal to 20, establishments in London with RatingValue greater than or equal to 4, the top 5 establishments with a RatingValue of 5 sorted by lowest hygiene score and nearest to "Penang Flavours," and the number of establishments in each Local Authority area with a hygiene score of 0.

Overall, the project involved data manipulation, database updates, and exploratory analysis using Python, PyMongo, and Jupyter Notebook, to provide valuable insights and recommendations to the magazine "Eat Safe, Love" for their future article focus.
