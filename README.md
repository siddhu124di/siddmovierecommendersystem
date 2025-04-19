# Movie Recommendation System 🎬

A content-based movie recommendation system built with Python and Streamlit. This app suggests similar movies based on user input using cosine similarity and displays movie posters via the TMDb API.

## Features
- **Personalized Recommendations**: Get a list of similar movies based on the movie you choose.
- **Movie Posters**: View movie posters fetched from the TMDb API.
- **Interactive UI**: Built with Streamlit for a user-friendly experience.

## Tech Stack
- **Python**: The programming language used to implement the system.
- **Streamlit**: For building the interactive web interface.
- **Scikit-learn**: Used for similarity calculations (cosine similarity).
- **TMDb API**: Provides movie data, such as movie posters, titles, and overviews.

## How It Works
1. **Input a Movie**: Select a movie from the search bar.
2. **Fetch Recommendations**: The system calculates cosine similarity to recommend movies that are similar in terms of content (e.g., genres, keywords).
3. **Display Results**: Recommended movies are displayed along with posters and additional information.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommender.git
