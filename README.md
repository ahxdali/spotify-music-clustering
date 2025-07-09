# spotify-music-clustering

A simple unsupervised machine learning project that groups Spotify tracks by their audio features using K-Means clustering and visualizes the results with PCA and artist word clouds.

## Dataset

This project uses the [Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) from Kaggle, containing over 110,000 tracks with various audio attributes and metadata.

## Features Used for Clustering

- danceability  
- energy  
- loudness  
- speechiness  
- acousticness  
- instrumentalness  
- liveness  
- valence  
- tempo  

## How to Run

1. Clone or download this repository.  
2. Upload `spotify_tracks.csv` dataset to your environment (e.g., Google Colab).  
3. Install dependencies if needed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn wordcloud
Run the notebook or script to preprocess data, apply K-Means clustering, reduce dimensionality with PCA, and generate visualizations.

Results
Elbow method plot to select optimal cluster count.

PCA scatter plot showing clusters of similar tracks.

Word clouds of top artists in each cluster.

Summary of average audio features per cluster.
```
Future Improvements
Explore different clustering algorithms (e.g., DBSCAN, Agglomerative).

Incorporate genre or popularity into analysis.

Build an interactive web app for cluster exploration.

Tune hyperparameters and use cross-validation.

Author
Ahad Ali
https://github.com/ahxdali
