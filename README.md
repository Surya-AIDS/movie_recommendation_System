🎬 Movie Recommender System

📌 Project Overview
This project is a Movie Recommender System built using Python and Streamlit that provides personalized movie recommendations along with posters. The system uses a precomputed similarity matrix to find movies similar to the one selected by the user and fetches movie posters from The Movie Database (TMDb) API. It offers an interactive and visually appealing interface for users to explore movie suggestions easily.

🎯 Business/Project Objective
To answer the core question:
"How can a system provide personalized movie recommendations based on user preferences and historical movie data?"
The system analyzes user-selected movies and recommends the top 5 movies that are most similar, helping users discover relevant movies they might enjoy.

🧰 Tools & Technologies Used

Python – Data processing, similarity computation, and backend logic

Streamlit – Interactive web interface

Pickle – Storing and loading precomputed similarity matrices and movie data

Requests – Fetching movie posters dynamically from TMDb API

📂 Project Structure

Movie-Recommender-System/
│
├── app.py                     # Streamlit application
├── model/
│   ├── movie_list.pkl          # Movie dataset
│   └── similarity.pkl          # Precomputed similarity matrix
├── README.md                   # Project description
└── requirements.txt            # Required Python packages


🔍 Key Features

Personalized movie recommendations using a precomputed similarity matrix

Dynamic fetching and display of movie posters via TMDb API

Top 5 recommendations displayed with movie titles and images

Interactive and user-friendly interface with Streamlit

📈 How It Works

Users select or type a movie from a dropdown list.

The system identifies the selected movie’s index and calculates similarity scores with other movies.

Top 5 most similar movies are determined and their posters are fetched from TMDb API.

Recommendations are displayed in a 5-column layout with titles and posters.

🚀 Project Impact

Demonstrates practical application of machine learning in recommendation systems

Provides an interactive experience for users to discover new movies

Shows integration of data processing, API handling, and web deployment

📎 How to Use This Repository

Clone the repository

Install dependencies using pip install -r requirements.txt

Run the Streamlit app using streamlit run app.py

Select a movie from the dropdown and click “Show Recommendation” to view personalized suggestions

🙌 Author
Surya Prakash P – B.Tech Artificial Intelligence & Data Science Student | Aspiring Data Scientist | AI & Analytics Enthusiast
