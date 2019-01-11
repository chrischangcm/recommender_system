# Recommender systems
Exploration of basic recommender systems as an in-class project using the [Booking Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/). This data is contained in the files BX-Book-Ratings.csv, BX-Books.csv and BX-Users.csv


## Data cleaning
Contained within [EDA_cleaning.ipynb](https://github.com/chrischangcm/recommender_system/blob/master/EDA_cleaning.ipynb).
Despite the misleading name, EDA is not included. Number of unique books reduced from around 320,000 to 4,533


## Model training
Contained within [Model_training.ipynb](https://github.com/chrischangcm/recommender_system/blob/master/Model_training.ipynb).
Basic implementation of Collaborative filtering, Content based filtering and Matrix factorization. Code for matrix factorization is mostly copied from [Albert Auyeung's fantastic repo](https://github.com/albertauyeung/matrix-factorization-in-python) with very minor edits. Output correlation matrices for collaborative/content based filtering are around 300-400MB and too large to upload but should not take too long to run. Timestamps are included in the notebook for reference.


## Recommendation Engines
Contained within [Recommendation_engines.ipynb](https://github.com/chrischangcm/recommender_system/blob/master/Recommendation_engines.ipynb).
Examples of how the previous models operate and how hybrid systems utilize the output of multiple models to generate recommendations.



### Note: Have not included notes/documentation for data cleaning and model training. Will update later
