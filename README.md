# 🎵 Intelligent Concert Performance Analytics and Vocal Insights Platform

## 📌 Project Overview
A data science and analytics platform that analyzes music performance data to predict song popularity, cluster genres, and derive vocal insights — built as a placement capstone project.

## 🛠️ Tech Stack
- **Python** — Data processing & ML
- **Pandas & NumPy** — Data manipulation
- **PostgreSQL** — Database & SQL analytics
- **Scikit-learn** — Machine learning models
- **Matplotlib & Seaborn** — Data visualization
- **Power BI** — Interactive dashboard

## 📊 Modules
| Module | Description | Status |
|--------|-------------|--------|
| Data Collection & Cleaning | Spotify dataset, 89,741 songs | ✅ Done |
| Exploratory Data Analysis | Genre trends, correlations, 5 charts | ✅ Done |
| SQL & ETL Pipeline | PostgreSQL integration, advanced queries | ✅ Done |
| Genre Clustering (K-Means) | 5 musical clusters identified | ✅ Done |
| Popularity Prediction | 3 models compared — RF wins | ✅ Done |
| Hit/Flop Classification | Binary classification with F1 improvement | ✅ Done |
| Model Improvement | Feature engineering, genre encoding | ✅ Done |
| Power BI Dashboard | 4 interactive visuals | ✅ Done |

## 📁 Dataset
- **Source:** Spotify Tracks Dataset (Kaggle)
- **Size:** 89,741 songs (after cleaning)
- **Features:** Danceability, Energy, Tempo, Loudness, Popularity, Genre and more

## 🔍 Key Findings

**1. Genre Analysis**
K-Pop is the most popular genre (avg popularity 59.36), followed by pop-film and metal. Genre context significantly improves ML model performance.

**2. Audio Feature Insights**
Acousticness is the single strongest predictor of popularity — stronger than danceability or energy. Energy and loudness are strongly correlated (confirmed via heatmap and scatter plot).

**3. Song Clustering**
K-Means clustering revealed 5 distinct musical groups:
- Cluster 0: Acoustic & Calm tracks
- Cluster 1: High Energy / Live performances
- Cluster 2: Spoken Word / Podcast-style (smallest, lowest popularity)
- Cluster 3: Mainstream Pop/Dance (largest, highest popularity)
- Cluster 4: Instrumental / Ambient

**4. Popularity Prediction**
| Model | R² Score |
|-------|----------|
| Linear Regression | 0.081 |
| Gradient Boosting | 0.166 |
| Random Forest | **0.263** |

Random Forest outperformed all models. Audio features alone explain ~26% of popularity variance — remaining 74% likely driven by artist fame, marketing, and playlist placement.

**5. Hit/Flop Classification**
Adjusting hit threshold from 70 to 60 improved F1 score by 2x (0.134 → 0.267), demonstrating that choosing the right evaluation metric matters more than raw accuracy.

## 📈 Power BI Dashboard
4-page interactive dashboard connected to PostgreSQL:
- Genre popularity comparison
- Treemap of all genres
- Danceability vs Popularity scatter
- Energy vs Loudness correlation
- Top artists by popularity

## 👩‍💻 Author
Vidisha Bhat — Final Year ENTC Engineering Student, SPPU
