Movie Recommendation System

📌 Project Overview

This project explores different machine learning and deep learning approaches to build a movie recommendation system using the MovieLens Latest Small dataset. It focuses on predicting user ratings and recommending movies based on user preferences and similarities between users and movies.

The project implements collaborative filtering techniques, dimensionality reduction, and a neural network-based rating prediction model.

🎯 Objectives

- Explore user preferences and movie rating patterns.
- Identify similarities between users and movies.
- Generate movie recommendations based on rating data.
- Apply dimensionality reduction to the user-item rating matrix.
- Build and evaluate a neural network for movie rating prediction.

📊 Dataset

The project uses the MovieLens Latest Small dataset, which contains:

- 100,836 movie ratings
- 610 users
- 9,724 movies

The dataset includes user ratings and movie information used to analyze preferences and develop recommendation approaches.

🛠️ Technologies & Libraries

- Python
- Pandas — Data manipulation and analysis
- NumPy — Numerical computations
- Matplotlib — Data visualization
- Scikit-learn — Cosine similarity, TruncatedSVD, and evaluation
- TensorFlow / Keras — Neural network development

⚙️ Methods Implemented

1. User-Based Collaborative Filtering

User similarities are calculated using cosine similarity. Recommendations are generated based on the ratings of similar users.

2. Item-Based Similarity Analysis

Cosine similarity is used to measure relationships between movies based on their rating patterns.

3. Dimensionality Reduction with TruncatedSVD

Truncated Singular Value Decomposition (TruncatedSVD) is applied to the user-item rating matrix to explore latent patterns in user preferences and predict ratings.

4. Neural Network-Based Rating Prediction

A neural network model is developed using TensorFlow/Keras. It includes user and movie embedding layers, concatenation, dense layers, and dropout to learn representations and predict movie ratings.

📈 Evaluation

The rating prediction approach using TruncatedSVD is evaluated using Root Mean Squared Error (RMSE).

- Reported RMSE: 1.01

The neural network model is also trained to explore deep learning techniques for rating prediction.

🚀 Key Learning Outcomes

- Understanding user-item rating matrices.
- Implementing user-based and item-based similarity methods.
- Applying dimensionality reduction to recommendation data.
- Building embedding-based neural networks.
- Evaluating rating prediction using RMSE.
- Working with Python machine learning and deep learning libraries.

▶️ How to Run

1. Clone or download this repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run the cells sequentially.

Install the main dependencies with:

pip install pandas numpy matplotlib scikit-learn tensorflow jupyter

📁 Project Structure

Movie-Recommendation-System/
├── recommender_system.ipynb
└── README.md

Note: Replace "recommender_system.ipynb" with the actual notebook filename in your repository.

👩‍💻 Author

Developed as a machine learning project to explore collaborative filtering, dimensionality reduction, and neural network-based movie rating prediction.
