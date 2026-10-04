# Movie Recommendation System

A Machine Learning-based Movie Recommendation System that recommends movies to users based on the similarity between movie content such as overview, genres, keywords, cast, and crew.

## Project Overview

The Movie Recommendation System uses content-based filtering to find movies that are similar to a movie selected by the user.

The system analyzes movie-related information and converts textual features into numerical representations using CountVectorizer. Cosine Similarity is then used to measure the similarity between movies and generate recommendations.

## Objectives

* Build a content-based movie recommendation system.
* Analyze movie metadata and textual information.
* Convert text data into numerical features.
* Calculate similarity between movies.
* Recommend movies similar to the user's selected movie.

## Dataset

The dataset contains the following features:

| Feature  | Description                         |
| -------- | ----------------------------------- |
| movie_id | Unique identifier of the movie      |
| title    | Movie title                         |
| overview | Description or summary of the movie |
| genres   | Movie genres                        |
| keywords | Keywords related to the movie       |
| cast     | Main cast members                   |
| crew     | Crew members involved in the m      |
