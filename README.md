# Intelligent Recommender System Assignment - User-Based and Item-Based Collaborative Filtering

This repository contains the code, report, and analysis for an intelligent recommender system assignment. The project demonstrates the implementation of user-based and item-based collaborative filtering techniques to provide movie recommendations based on user ratings.

## Project Overview

In this assignment, we implemented a recommendation system using two collaborative filtering methods:
- **User-Based Collaborative Filtering**: Recommends items by identifying similar users based on their ratings.
- **Item-Based Collaborative Filtering**: Recommends items similar to those the user has already rated highly.

We applied similarity measures (Cosine Similarity and Pearson Correlation) to analyze user and item relationships, generate recommendations, and evaluate the recommendation overlap between methods.

## Features

- **Data Collection**: Filtered movie data using predefined criteria for quality and popularity, ensuring robust recommendations.
- **Similarity Computation**: Calculated Cosine Similarity and Pearson Correlation for users and items to understand preference patterns.
- **Recommendation Generation**: Provided top-N recommendations for each user based on both similarity methods.
- **Recommendation Evaluation**: Compared recommendation overlap between Cosine and Pearson methods to assess the consistency of recommendations.

## File Structure

- **code/**: Contains Python scripts used to generate recommendations, compute similarity, and evaluate recommendation overlap.
- **report/**: PDF report with in-depth analysis, methodology, and results of the recommendation system.
- **results/**: Contains outputs such as similarity matrices, recommendation lists, evaluation tables, and visualizations.

## Installation

1. Clone this repository.
   ```bash
   git clone https://github.com/yourusername/repo-name.git
