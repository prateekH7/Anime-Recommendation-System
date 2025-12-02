## Anime Recommendation System (NLP + ML)

This project builds a content-based recommendation engine that suggests similar anime titles using TF-IDF vectorization and cosine similarity.
The model analyzes anime descriptions, genres, ratings, and user reviews to identify similarity patterns and return top recommendations.

📌 Project Overview

Dataset contains anime metadata (titles, genres, ratings, popularity).

TF-IDF converts text descriptions into numerical vectors.

Cosine similarity finds the closest anime titles based on vector similarity.

The system provides top 5 recommendations for any selected anime.

🧠 Tech Stack

Python

Pandas

NumPy

Scikit-learn

TF-IDF Vectorizer

Cosine Similarity

Jupyter Notebook

📂 Project Structure
Anime-Recommendation-System/
│── data/
│     └── anime.csv
│── notebooks/
│     └── Anime-Project.ipynb
│── src/
│── requirements.txt
│── README.md

🚀 How It Works

Load and clean the dataset

Combine metadata (genres, synopsis, etc.)

Generate TF-IDF matrix

Calculate similarity scores

Return the most similar anime titles

📊 Example Output

Input: Naruto
Top Recommendations:

Bleach

One Piece

Fairy Tail

Hunter x Hunter

Soul Eater

📈 Future Improvements

Better NLP embedding (BERT, Sentence Transformers)

Hybrid recommendation system

Web app interface (Streamlit)

👤 Author

Pratik Harlikar
Master of Data Analytics
New Mexico State University
