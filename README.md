# Movie Recommendation System
## Overview
This project implements a movie recommendation system using content-based filtering techniques, specifically TF-IDF vectorization and cosine similarity. The system suggests movies similar to a user's favorite choice based on shared content features such as genres, keywords, taglines, cast, and director.

## Key Features
·Loads movie data from a CSV file into a pandas DataFrame.<br>
·Pre-processes and cleanses the data, handling missing values in selected features.<br>
·Combines selected textual features into a single feature string for each movie.<br>
·Converts the textual data into TF-IDF feature vectors using scikit-learn's TfidfVectorizer.<br>
·Calculates cosine similarity scores between movies' TF-IDF vectors to measure similarity.<br>
·Accepts user input for their favorite movie and suggests similar movies based on cosine similarity.<br>


## Requirements
·Python 3.x <br>
·NumPy <br>
·pandas<br>
·scikit-learn<br>