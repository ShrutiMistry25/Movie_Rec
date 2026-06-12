# Movie Recommender System

A content-based movie recommendation system built with Streamlit. It recommends movies based on plot overview, genres, keywords, cast, and crew using cosine similarity.

## How It Works

1. Processes TMDB 5000 movie metadata (overview, genres, keywords, cast, crew)
2. Combines text features into tags and vectorizes them using CountVectorizer
3. Computes cosine similarity between all movie pairs
4. Recommends top 5 similar movies for any selected movie
5. Fetches movie posters via TMDB API

## Tech Stack

- **Python** (Pandas, Scikit-learn, Numpy)
- **Streamlit** for UI
- **TMDB API** for movie posters

## Run Locally

```bash
pip install streamlit requests pandas scikit-learn
python -m streamlit run app.py
```

