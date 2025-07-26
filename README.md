🎬 Movie Recommender System
Welcome to the Movie Recommender System, a web application built using Streamlit that suggests movies similar to your favorites — complete with posters!

<div align="center"> <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" /> <img src="https://img.shields.io/badge/Streamlit-1.0-red.svg" /> <img src="https://img.shields.io/badge/Machine%20Learning-Cosine%20Similarity-yellow.svg" /> </div>
🔍 Features
🔎 Search Your Favorite Movie
Select a movie from the dropdown list.

🤖 Get 5 Smart Recommendations
See five similar movies based on content similarity.

🖼️ Visual Appeal with Posters
Recommendations come with movie posters fetched from TMDb (The Movie Database).

🚀 Fast and Lightweight
Built using Streamlit for quick, interactive use.

🧠 How It Works
Uses cosine similarity on movie metadata like genre, cast, director, etc.

A precomputed similarity matrix helps to efficiently suggest top related movies.

Posters are fetched in real time from TMDb API using the movie ID.

🛠️ Tech Stack
Frontend: Streamlit

Backend: Python (Pandas, Requests)

Machine Learning: Content-based filtering with cosine similarity

API: TMDb API

📁 Project Structure
movies-recommender-system/
│
├── app.py                  # Main Streamlit application
├── movies_dict.pkl         # Movie metadata (titles, ids, etc.)
├── similarity.pkl          # Precomputed similarity matrix
├── movie-recommender-system.ipynb  # Notebook for building logic (optional)
├── README.md               # You're reading it!
🚀 How to Run
Install dependencies:


pip install streamlit pandas requests
Run the Streamlit app:

streamlit run app.py
Open in browser: Your default browser will open automatically. If not, go to:

arduino
Copy
Edit
http://localhost:8501
🔑 TMDb API Key
Make sure to replace the placeholder API key in app.py:

python
Copy
Edit
api_key = "your_actual_tmdb_api_key"
Get your free key here: TMDb API Signup

📸 Preview

🙌 Acknowledgements
TMDb for providing movie data and poster images.

Inspired by content-based filtering techniques in recommendation systems.

.

📌 Future Improvements
🎯 Add user rating input for better hybrid recommendations.

🔍 Add search functionality instead of dropdown.


