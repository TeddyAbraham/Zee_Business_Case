# 🎬 Personalized Movie Recommender System

This project builds a personalized movie recommender system using the **MovieLens** dataset. It applies multiple recommendation techniques to enhance user experience.

## 📂 Dataset Description

The project uses the following files from the MovieLens dataset:

- `ratings.csv` – User ratings (`UserID`, `MovieID`, `Rating`, `Timestamp`)
- `users.csv` – User demographics (`UserID`, `Gender`, `Age`, `Occupation`, `Zip-code`)
- `movies.csv` – Movie details (`MovieID`, `Title`, `Genres`)

## 🧠 Recommendation Techniques

- **Collaborative Filtering**
  - *Item-based:* Pearson Correlation & Cosine Similarity
  - *User-based:* Pearson Correlation
- **Matrix Factorization**
  - Implemented using the `Surprise` library

## ⚙️ Key Components

- Data preprocessing and merging
- Exploratory Data Analysis (EDA)
- Implementation of:
  - Item-based recommendation
  - User-based recommendation
  - Matrix factorization model
- Embedding visualizations for users and items
- Evaluation using:
  - **RMSE** (Root Mean Squared Error)
  - **MAPE** (Mean Absolute Percentage Error)
