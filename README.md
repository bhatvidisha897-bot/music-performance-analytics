# 🎵 Intelligent Concert Performance Analytics and Vocal Insights Platform

## 📌 Project Overview
A data science and analytics platform that analyzes music performance data to predict song popularity, cluster genres, and derive vocal insights — built as a placement capstone project.

## 🛠️ Tech Stack
- **Python** — Data processing & ML
- **Pandas & NumPy** — Data manipulation
- **PostgreSQL** — Database & SQL analytics
- **Scikit-learn** — Machine learning models
- **Matplotlib & Seaborn** — Data visualization
- **Power BI** — Interactive dashboard (upcoming)

## 📊 Modules
| Module | Description | Status |
|--------|-------------|--------|
| Data Collection & Cleaning | Spotify dataset, 89,741 songs | ✅ Done |
| Exploratory Data Analysis | Genre trends, correlations | ✅ Done |
| SQL & ETL Pipeline | PostgreSQL integration | ✅ Done |
| Genre Clustering (K-Means) | Unsupervised song grouping | ✅ Done |
| Popularity Prediction | Regression models | ✅ Done |
| Hit/Flop Classification | Binary classification | ✅ Done |
| Power BI Dashboard | Interactive visuals | ⏳ Upcoming |

## 📁 Dataset
- **Source:** Spotify Tracks Dataset (Kaggle)
- **Size:** 89,741 songs (after cleaning)
- **Features:** Danceability, Energy, Tempo, Loudness, Popularity, Genre and more

## 🔍 Key Findings

**Genre Clustering:** K-Means clustering on 9 audio features revealed 5 distinct musical groups — from acoustic/calm tracks to high-energy mainstream pop, with the "mainstream pop" cluster showing the highest average popularity.

**Popularity Prediction:** Random Forest outperformed Linear Regression (R² 0.189 vs 0.030), showing that the relationship between audio features and popularity is non-linear. Acousticness emerged as the single strongest predictor — stronger than danceability or energy.

**Hit/Flop Classification:** Initial model showed high accuracy (83.8%) but poor precision (8%) due to class imbalance — a classic real-world ML problem. Adjusting the hit threshold improved F1 score by over 2x, demonstrating the importance of choosing the right evaluation metric over raw accuracy.

## 👩‍💻 Author
Vidisha Bhat — Final Year Engineering Student
