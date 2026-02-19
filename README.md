🎬 Movie Recommender System

A Movie Recommendation System built with Python and Streamlit that provides personalized movie suggestions along with posters using machine learning and the TMDb API.

Features

Suggests top 5 movies similar to the selected movie.

Fetches and displays movie posters from TMDb.

Interactive UI with Streamlit.

Installation

Clone the repository:

git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender


Create a virtual environment (optional):

python -m venv env
source env/bin/activate  # Linux/Mac
env\Scripts\activate     # Windows


Install dependencies:

pip install -r requirements.txt


Run the app:

streamlit run app.py

How It Works

Select or type a movie from the dropdown.

Click Show Recommendation.

The system finds similar movies using a similarity matrix.

Posters and titles of the top 5 recommended movies are displayed.

Project Structure
movie-recommender/
│
├── app.py                 # Streamlit app
├── model/
│   ├── movie_list.pkl     # Movie dataset
│   └── similarity.pkl     # Precomputed similarity matrix
├── requirements.txt
└── README.md

Dependencies

Python 3.x

Streamlit

Pandas

Requests

Pickle

Author

Surya Prakash P – B.Tech AI & Data Science Student

GitHub: [Your GitHub URL]

LinkedIn: [Your LinkedIn URL]
