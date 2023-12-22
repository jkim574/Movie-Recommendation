# Advanced Movie Recommendation Engine

## Overview
Developed an innovative movie recommendation engine with data science and machine learning techniques. The project entailed processing and analyzing movie metadata and user ratings data to deliver personalized movie recommendations.

## Key Features

### Data Processing and Analysis 
- Utilized **Pandas** and **NumPy** for sophisticated data manipulation and analysis.
- The process involved loading and preprocessing datasets including movie metadata and user ratings, emphasizing movies in the English language.
- A pivot table was created to transform the data into a user-item matrix, in order to set the stage for the recommendation algorithms.

### Pearson Correlation-Based Recommendation
- Initially implemented a recommendation system using the Pearson Correlation coefficient.
- This method calculated similarities between movies based on user ratings, identifying movies with similar rating patterns.

### Advancement to K-Nearest Neighbors (KNN)
- Evolved the system by integrating a KNN-based approach.
- This shift represented a significant enhancement, moving from simple linear correlation to a more nuanced method considering the ‘k’ most similar movies.
- The KNN model was implemented using a combination of Pearson Correlation for similarity measurement and genre-based weighting, offering a more robust recommendation mechanism.

### Genre-Based Adjustments
- Incorporated genre-based adjustments in both Pearson Correlation and KNN methodologies.
- This aspect ensured that the recommendations were not only based on user rating patterns but also considered content similarity, thereby catering to the user's genre preferences.

## Objective
The primary objective was to develop a sophisticated and user-centric movie recommendation engine. By transitioning from Pearson Correlation to KNN, the project aimed to enhance the accuracy and personalization of movie suggestions. This progression ensured a more refined and user-tailored experience, addressing the complexities inherent in user preferences and movie attributes.

## Technologies Used
- Python
- Pandas
- NumPy
- JSON

## Dataset
- The Movies Dataset: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset
