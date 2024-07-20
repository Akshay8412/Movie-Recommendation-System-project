# Movie Recommendation System

## Overview

Welcome to the Movie Recommendation System project! This project provides personalized movie recommendations based on a given movie title. By leveraging machine learning techniques and a similarity matrix, the system suggests movies that are similar to the one specified by the user.

## Features

- **Personalized Recommendations**: Given a movie title, the system suggests other movies that are similar.
- **Similarity Matrix**: Utilizes a precomputed similarity matrix to find the most similar movies.
- **Error Handling**: Gracefully handles cases where the specified movie is not found in the dataset.

## Project Structure

- `data/`: Directory containing the dataset files.
- `notebooks/`: Jupyter notebooks used for data exploration and model training.
- `src/`: Source code for the recommendation system.
  - `recommendation.py`: Contains the core recommendation function.
- `README.md`: Project description and setup instructions.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/movie-recommendation-system.git
   cd movie-recommendation-system
