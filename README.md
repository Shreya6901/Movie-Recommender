# Movie-Recommender System

This code recommends top 5 movies based on content based similarity

# Content-Based Movie Recommender System

A Content-Based Recommender System suggests movies similar to those a user has liked. It determines which movies are most similar by using similarity scores.

# Similarity Score:

A similarity score is a numerical value ranging from zero to one that indicates how similar two items are. This score is determined by comparing the text details of both items. Essentially, the similarity score measures the likeness between the text descriptions of the two items. One common method for calculating this score is cosine similarity.

# How Cosine Similarity Works:

Cosine similarity is a metric used to measure how similar documents are, regardless of their size. Mathematically, it calculates the cosine of the angle between two vectors projected in a multi-dimensional space. The advantage of cosine similarity is that even if two similar documents are far apart in terms of Euclidean distance (due to their size), they can still be close in orientation. A smaller angle between the vectors results in a higher cosine similarity.

# Python Libraries Used:

- Pandas
- Numpy
- Natural language toolkit (NLTK)
- Scikit Learn

# Data Source

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
