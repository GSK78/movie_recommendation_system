# Movie Recommendation System

This project is a Python-based Movie Recommendation System that suggests movies to users based on their preferences. It uses machine learning techniques, specifically content-based filtering, to recommend movies similar to a user's favorite movie, by analyzing various movie features.

## Description

The system loads a dataset of movies with attributes such as genre, keywords, tagline, cast, and director. It combines these features and applies TF-IDF vectorization to convert text data into numerical format. Using cosine similarity, it calculates similarity scores between movies to suggest recommendations.

Users input their favorite movie name, which the system matches to the closest available title in the dataset. Then it retrieves and displays a list of movies similar to the selected movie.

## Features

- Loads movie data from a CSV file.
- Uses combined movie attributes for recommendations.
- Applies TF-IDF vectorization for feature extraction.
- Calculates cosine similarity to find movie similarity.
- Accepts user input and handles approximate matching of movie titles.
- Displays top 30 or top 10 recommended movies based on user interaction.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn

## Installation

Install necessary packages via pip:

```bash
pip install pandas numpy scikit-learn