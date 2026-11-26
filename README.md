# Movie Recommendation System using Matrix Factorization

## Overview

This project focuses on building a movie recommendation system using Collaborative Filtering and Matrix Factorization techniques.

The goal is to explore user preferences, analyze movie ratings, and develop a recommendation model capable of predicting user preferences for movies they have not rated.

The project uses the **MovieLens 1M Dataset**.

## Dataset

The MovieLens 1M dataset contains:

- 6,040 users
- 3,706 movies
- 1,000,209 ratings
- Rating scale: 1 to 5

The dataset contains user ratings, movie information, and demographic information.

## Exploratory Data Analysis (EDA)

The initial analysis includes:

- Dataset structure and data inspection
- Distribution of movie ratings
- Distribution of ratings per user
- Distribution of ratings per movie
- Identification of the most rated movies
- User-Item Matrix construction
- Analysis of matrix sparsity

### Key Findings

| Metric | Value |
|---|---:|
| Users | 6,040 |
| Movies | 3,706 |
| Ratings | 1,000,209 |
| Matrix Dimensions | 6,040 × 3,706 |
| Matrix Sparsity | 95.53% |

The User-Item Matrix is highly sparse, with only 4.47% of possible user-movie interactions containing ratings.

This presents an important challenge for collaborative filtering recommendation systems.

## Methodology

The project will explore the following approaches:

1. Exploratory Data Analysis
2. User-Item Matrix construction
3. Train/Test Split
4. Collaborative Filtering
5. Matrix Factorization
6. Singular Value Decomposition (SVD)
7. Model evaluation and comparison

## Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
matrix-factorization-project/
│
├── Movie_Recommender_System.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
└── data/
    └── (MovieLens dataset - not tracked by Git)
```

## Project Status

Currently, the project focuses on Exploratory Data Analysis and data preparation.

Matrix Factorization implementation and model evaluation are planned next.

## Future Improvements

- Implement Matrix Factorization models
- Compare recommendation algorithms
- Evaluate prediction accuracy using RMSE and MAE
- Generate personalized movie recommendations
- Analyze recommendation quality

## Author

**Rauan Yelubayeva**

GitHub: [@Rau2024](https://github.com/Rau2024)
