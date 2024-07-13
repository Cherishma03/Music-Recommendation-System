# Music-Recommendation-System


## Overview
This project presents a personalized music recommendation system based on matrix factorization, vectorization, and various machine learning algorithms. Our system combines collaborative filtering and content-based filtering techniques to recommend music to users by analyzing their listening history and song attributes. Additionally, it includes a plagiarism detection module to identify and manage copyright issues.

## Algorithms Used
- **Collaborative Filtering:** Utilizes user-item interactions to predict user preferences. Techniques include
Matrix Factorization (e.g., SVD, NMF)
User-based and Item-based filtering
- **Content-Based Filtering:** Recommends songs based on the similarity of song attributes using:
TF-IDF Vectorization
Cosine Similarity
- **Lyrics-Based Recommendation:** Uses Natural Language Toolkit (NLTK) for text preprocessing, vectorization, and similarity computation to recommend songs based on lyrical content.
## Datasets
- **Million Song Dataset (MSD):** Contains metadata and audio features for a million songs, used for collaborative filtering.
- **songdata.csv:** Contains song titles, artist names, release years, and lyrics, used for content-based filtering and lyrics-based recommendation.
