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

## Related Projects

- [AI Career Copilot](https://github.com/ShrutiMistry25/ai-career-copilot) — AI-powered career guidance platform with resume builder, interview prep, and learning recommendations.
- [Email Spam Classifier](https://github.com/ShrutiMistry25/Email_Spam) — ML-based email spam detection system.
- [Jarvis AI](https://github.com/ShrutiMistry25/Jarvis_Ai) — OpenAI-powered desktop voice assistant with speech recognition and TTS.
- [LLM Models](https://github.com/ShrutiMistry25/LLM_MODELS) — Collection of LLM experiments and implementations.
