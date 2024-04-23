# Movie Recommendations using LSTM

This repository contains code for a movie recommendation system implemented using LSTM (Long Short-Term Memory) networks. The recommendation system utilizes movie ratings provided by users to suggest similar movies to a given input.

## Table of Contents

- Introduction
- Dependencies
- Data
- Analysis
- Matrix Manipulation
- SVD (Singular Value Decomposition)
- Cosine Similarity
- Usage

## Introduction

The recommendation system is built using Python and relies on the LSTM architecture to analyze user ratings and suggest similar movies based on their preferences. The system employs various data manipulation and analysis techniques to achieve accurate recommendations.

## Dependencies

The code utilizes the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`

Ensure that these dependencies are installed in your Python environment before running the code.

## Data

The dataset used in this project comprises three main files:

- `ratings.dat`: Contains user ratings for movies.
- `movies.dat`: Provides information about movies, including title and genre.
- `users.dat`: Includes user demographic data such as gender, age, and occupation.

These files are loaded into Pandas dataframes for analysis.

## Analysis

The code conducts various analyses on the dataset, including:

- Aggregating ratings to find average ratings for each movie.
- Sorting movies based on average ratings.
- Analyzing differences in ratings between genders.

## Matrix Manipulation

The ratings data is structured into a matrix format for further analysis. Techniques such as normalization are applied to the ratings matrix.

## SVD (Singular Value Decomposition)

SVD is performed on the normalized ratings matrix to decompose it into its constituent matrices. This decomposition facilitates the computation of movie similarities.

## Cosine Similarity

Cosine similarity is calculated between movies based on their ratings. This similarity metric is used to identify movies similar to a given input.

## Usage

To utilize the recommendation system:

1. Ensure all dependencies are installed.
2. Run the provided code in a Python environment.
3. Follow the prompts or modify the code to suit your specific requirements.
4. Explore the recommendations generated by the system.

