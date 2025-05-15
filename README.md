# Spotify Song Recommendation System 🎵

This is a machine learning project that recommends songs based on audio features using **KMeans Clustering** and **PCA** for visualization.

## 🔍 Features Used
- Danceability
- Energy
- Loudness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo
- Speechiness

## 📊 ML Techniques
- Unsupervised Learning: KMeans Clustering
- Dimensionality Reduction: PCA (2D)
- Cosine Similarity for Recommendation

## 💡 How It Works
1. Spotify songs dataset is clustered based on audio features.
2. User inputs a song.
3. The model recommends similar songs from the same cluster.

## 📁 Dataset
Used: `SpotifyFeatures.csv`  
Source: Kaggle or [Spotify API](https://developer.spotify.com/documentation/web-api/)

## 📌 Requirements
- Python 3.x
- pandas
- scikit-learn
- seaborn
- matplotlib

Install with:
```bash
pip install -r requirements.txt
