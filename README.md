# 🎬 Movie Recommendation System (Neural Collaborative Filtering)

## 1. Overview

This project builds a **collaborative filtering-based movie recommendation system** using Keras and deep learning techniques. It utilizes user and movie embeddings to predict whether a user would rate a movie positively. The model is trained using the popular MovieLens dataset and aims to learn latent features representing user preferences and item characteristics.

## 2. Features

- Reads and processes data from `movies.dat`, `ratings.dat`, and `users.dat`
- Maps user and movie IDs to continuous indices
- Constructs a **neural collaborative filtering model** using embedding layers
- Predicts binary ratings (like/dislike) based on a threshold (rating ≥ 4)
- Evaluates model using classification metrics: accuracy, precision, recall, F1-score
- Calculates **RMSE** for regression-based evaluation

## 3. Tech Stack

- **Python**
- **Keras / TensorFlow**
- **Pandas & NumPy**
- **Scikit-Learn**

## 4. Results & Findings

- The neural network achieved reliable classification performance on the MovieLens dataset.
- Embedding-based latent features helped learn implicit relationships between users and movies.
- Evaluation Metrics include:
  - ✅ **Accuracy**
  - 🎯 **Precision / Recall / F1-Score**
  - 📉 **Root Mean Squared Error (RMSE)**

## 5. Future Enhancements

- Implement deeper architectures (e.g., Neural Collaborative Filtering with MLP layers)
- Add side features (e.g., genres, demographics, tags)
- Build a front-end UI to allow users to get movie recommendations
- Train on larger datasets (e.g., MovieLens 1M or 20M)
- Add support for ranking-based metrics (e.g., MAP, NDCG)

---

**Note:** The `.dat` files should use `::` as the separator and be encoded in `ISO-8859-1`. Make sure to download the [MovieLens 100K dataset](https://grouplens.org/datasets/movielens/) and place it in your working directory before running the code.
