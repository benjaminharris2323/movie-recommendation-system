# Movie Recommendation System

A movie recommendation system built using the MovieLens 100K dataset. This project compares multiple recommendation approaches, including popularity-based recommendations, item-item collaborative filtering, and matrix factorization using Singular Value Decomposition (SVD).

## Dataset

MovieLens 100K Dataset

- 100,000 ratings
- 943 users
- 1,682 movies
- Ratings on a 1–5 scale

## Project Objectives

- Explore movie rating behavior
- Build recommendation models of increasing complexity
- Compare collaborative filtering and matrix factorization approaches
- Demonstrate data science and machine learning techniques

## Methods

### Popularity-Based Recommender

Generated recommendations using average movie ratings and minimum rating thresholds.

### Item-Item Collaborative Filtering

Constructed a user-movie matrix and used Pearson correlation to identify movies with similar rating patterns.

### Matrix Factorization (SVD)

Applied TruncatedSVD to learn latent movie features and generate recommendations based on learned similarity relationships.

## Results

Key findings include:

- Popularity-based recommendations provide a strong baseline.
- Filtering movies with fewer than 100 ratings significantly improves recommendation quality.
- Collaborative filtering successfully identified intuitive movie relationships.
- SVD captured broader similarity patterns and provides a more scalable recommendation framework.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

## Future Improvements

- User-based collaborative filtering
- Content-based recommendation systems
- Hybrid recommendation approaches
- Hyperparameter tuning
- Web application deployment

## Author

Benjamin Harris

M.S. Business Analytics  
University of Cincinnati