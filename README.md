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

# Movie Recommender System Setup Guide

## Prerequisites

1. **Python**: Ensure Python 3.x is installed on your system.
2. **Git**: Ensure Git is installed to clone the repository.
3. **Jupyter Notebook**: Ensure Jupyter Notebook is installed.

## Step-by-Step Instructions

1. **Clone the Repository**:
   
   Open a terminal (or command prompt) and run:
   ```sh
   git clone https://github.com/sadhana937/Movie-recommender-system.git
   cd Movie-recommender-system
   ```

2. **Install Required Dependencies**:
   
   Assuming the repository includes a `requirements.txt` file, run:
   ```sh
   pip install -r requirements.txt
   ```

3. **Run Jupyter Notebook**:
   
   Start the Jupyter Notebook server by running:
   ```sh
   jupyter notebook
   ```
   
   This will open a new tab in your web browser with the Jupyter interface.

4. **Open and Run Notebooks Sequentially**:
   
   In the Jupyter interface, navigate to the directory where the notebooks (`01- Acquire.ipynb` to `14-Image-Features.ipynb`) are located. Open each notebook one by one and run all cells sequentially. To run all cells in a notebook:
   - Open the notebook.
   - In the menu, go to `Cell` -> `Run All`.

## Troubleshooting

- If you encounter any issues with library installations, ensure the correct versions are installed as specified in the notebooks.
- Verify that the dataset is correctly placed in the required directory and that the paths in the notebooks match the dataset location.
- Check for any missing files or dependencies and install them as needed.

By following these steps, you should be able to set up and run the Movie Recommender System using the Jupyter notebooks provided in the repository.
```
