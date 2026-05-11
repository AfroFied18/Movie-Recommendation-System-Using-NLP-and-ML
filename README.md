# Movie Recommendation System

A content-based movie recommendation system built using NLP and Machine Learning.

## Features
- Content-based recommendation
- NLP preprocessing
- CountVectorizer
- Cosine similarity
- Streamlit web app

## Tech Stack
- Python
- Pandas
- Scikit-learn
- Streamlit
- NLP

## How It Works
Movie metadata such as genres, cast, crew, and keywords are combined into tags. These tags are vectorized using CountVectorizer, and cosine similarity is used to recommend similar movies.

## Run Locally

```bash
pip install -r requirements.txt
python -m streamlit run app.py
```
