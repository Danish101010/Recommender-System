# Movie Recommender System

## Overview
This project focuses on building a movie recommender system using a combination of content-based and collaborative filtering techniques. The system aims to provide personalized movie recommendations to users based on their preferences and past interactions.

## Features
- **Content-Based Filtering**: Utilizes movie metadata such as genre, actors, directors, and plot summaries to recommend similar movies based on user preferences.
- **Collaborative Filtering**: Analyzes user-item interactions and generates recommendations based on the behavior of similar users or items.
- **Deep Autoencoders**: Incorporates deep learning models such as autoencoders to enhance collaborative filtering performance and provide more accurate recommendations.

## Techniques Used
- Machine Learning Algorithms: Implemented KNN with cosine similarity, matrix factorization (e.g., SVD), and deep autoencoders for collaborative filtering.
- Data Preprocessing: Handled missing values, outlier detection, and data normalization to ensure robustness of the system.

## Implementation
The recommender system is implemented using Python programming language and various libraries such as NumPy, Pandas, Scikit-learn, and TensorFlow.

### Steps:
1. Data Collection: Gathered movie metadata and user-item interaction data from suitable sources.
2. Data Preprocessing: Cleaned and preprocessed the data to remove inconsistencies and prepare it for analysis.
3. EDA : Did Comprehensive exploratory data analysis on MovieLens Dataset.
4. Feature Extraction: Utilized Autoencoders and factorization techniques to extract relevant features from movie metadata.
5. Model Development: Implemented content-based and collaborative filtering models using appropriate machine learning algorithms.
6. Evaluation: Tested the models using metrics such as precision, recall, and mean absolute error to assess their accuracy and effectiveness.
   
## Future Improvements
- Incorporate hybrid recommender system techniques combining content-based and collaborative filtering approaches.
- Implement real-time updates to adapt to changing user preferences and trends.
- Explore advanced deep learning architectures for better feature representation and recommendation accuracy.

## Paper Reference
Used Deep AutoRec paper for this project

