# 🎯 Recommender System

This project implements a movie recommender system using collaborative filtering techniques. It includes both memory-based and model-based approaches, namely **user-based k-Nearest Neighbors (k-NN)** and **Matrix Factorization using Stochastic Gradient Descent (SGD)**. The system reads user rating data from CSV files, predicts ratings, and generates personalized top-N recommendations.

---

## 🏷️ Badges

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/ML-Recommender%20System-green)
![k-NN](https://img.shields.io/badge/Algorithm-k--Nearest%20Neighbors-informational)
![Matrix Factorization](https://img.shields.io/badge/Algorithm-Matrix%20Factorization-purple)
![Evaluation](https://img.shields.io/badge/Metric-RMSE-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Interface](https://img.shields.io/badge/Interface-CLI-lightgrey)
![Project Type](https://img.shields.io/badge/Type-Academic--Project-blueviolet)

---

## 💡 Key Features

- 📥 Load user-item rating data from CSV files
- 📈 Predict unseen ratings using:
  - User-user collaborative filtering (k-NN + cosine similarity)
  - Matrix factorization (latent factor model)
- 🧠 Generate personalized top-N recommendations
- 📊 Evaluate model accuracy using RMSE
- 🧱 Modular and extendable Python codebase

---

## 📁 Dataset Format

The system expects a CSV file with the following structure:

| user_id | item_id | rating | timestamp |
|---------|---------|--------|-----------|
| 1       | 101     | 4.0    | 874965758 |

> Example datasets: MovieLens 100K, custom CSV files, etc.

---

## 🧪 Evaluation

The system uses **Root Mean Squared Error (RMSE)** to evaluate the prediction performance on a test/validation split.

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/recommender-system.git
cd recommender-system
```

### 📌 To Use:
- Save this as your `README.md` in your root folder.
- Replace any placeholder GitHub link or path with your actual usernames and structure if needed.

