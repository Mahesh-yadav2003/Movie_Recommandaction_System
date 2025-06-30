# 🎬 Movie Recommendation System
This project is a content-based movie recommendation system built using Python, machine learning, and Streamlit for the user interface. It recommends similar movies based on the selected movie using a similarity score.

🚀 Key Features:
Recommends top 5 similar movies based on content.

Uses TF-IDF / CountVectorizer and cosine similarity techniques.

Clean and interactive Streamlit web app.

Pre-trained model stored using Pickle for fast performance.

Includes exploratory data analysis and preprocessing.

🛠️ Technologies Used:
Python

Pandas, NumPy, Scikit-learn

Pickle

Streamlit

NLP techniques (CountVectorizer / TF-IDF + Cosine Similarity)

📂 Files in the Repository:
app.py: Streamlit web app code.

movie_recommender.pkl: Serialized similarity model.

movies.csv: Dataset containing movie information.

README.md: Project documentation (you are here!).

💡 How It Works:
User selects a movie from the dropdown.

The model finds the most similar movies based on genres, keywords, cast, etc.

Recommended movies are displayed with their titles (optionally with posters).
