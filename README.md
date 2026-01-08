A content-based movie recommendation system built with Python, NLP and Scikit-learn that suggests similar movies based on storyline similarity using TF-IDF Vectorization and Cosine Similarity.



🔍 Why This Project?

Movie recommendation systems are widely used by platforms like Netflix and Amazon Prime.
This project demonstrates how Machine Learning + NLP can be used to build a recommendation engine using movie descriptions.


🚀 Key Features

Content-based movie recommendations

NLP-based text similarity

TF-IDF Vectorization

Cosine Similarity scoring

Case-insensitive movie search

Fast and lightweight implementation


🧠 Recommendation Technique

Filtering Type: Content-Based Filtering

Text Feature: Movie overview (storyline)

ML Techniques Used:

TF-IDF Vectorizer

Cosine Similarity

Movies with similar story descriptions are recommended.


📁 Dataset Details

Dataset: TMDB 5000 Movies Dataset

Source: Kaggle

Provided by: TMDB (The Movie Database)

Records: ~5,000 movies

Dataset contains movie titles, overviews, genres, popularity, ratings, and more.


🛠️ Tech Stack

Python

Pandas

NumPy

Scikit-learn

Google Colab


📂 Project Structure
Movie-Recommendation-System/
│
├── tmdb_5000_movies.csv
├── movie_recommendation.ipynb
├── README.md


⚙️ How It Works

Load and preprocess movie data

Clean and vectorize movie overviews

Compute cosine similarity matrix

Match user input movie

Recommend top similar movies


🧪 Sample Output
recommend_movie("Avatar")

Output:
The Matrix
Apollo 18
Tears of the Sun
The Inhabited Island
The American


📈 Accuracy & Reliability

Uses proven NLP similarity techniques

Stable and consistent recommendations

Industry-relevant approach

🔮 Future Improvements

Genre-based recommendations

Hybrid recommendation (ratings + content)

Web app using Streamlit

User personalization

👩‍💻 Author

Deepanshi Jindal

B.Tech(AI & DS)

