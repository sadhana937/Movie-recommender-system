# Movie Recommendation System

## Introduction
In this project, we implement a movie recommendation system leveraging the extensive MovieLens dataset. Our goal is to provide personalized movie recommendations tailored to individual preferences.

## Dataset Description
The MovieLens dataset consists of 1,000,209 ratings from 6,040 users on approximately 3,900 movies. It provides a rich source of user interaction data crucial for training recommendation models.

## Algorithms Used
Variety of algorithms are employed to generate recommendations:
- Baseline model: Utilizes mean ratings and popularity to suggest movies.
- Linear Matrix Factorization: Decomposes user-item interaction matrices to capture latent factors.
- Deep Neural Collaborative Filtering: Employs neural networks to learn embeddings directly from raw interaction data.
- Others: Non-Negative Matrix Factorization, Implicit Matrix Factorization, etc.

## Literature Review
Insights are drawn from studies such as "Enhancing Collaborative Filtering with User Demographics" and "Matrix Factorization Techniques for Personalized Content Delivery" to inform our approach.

## Evaluation
Models are evaluated using metrics like RMSE, Precision@k, and NDCG to ensure the quality and relevance of recommendations.

## Citation
We acknowledge the contribution of F. Maxwell Harper and Joseph A. Konstan's work on the MovieLens dataset.
