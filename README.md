Movie Recommender System

Overview: This Movie Recommender System suggests movies based on user preferences. It uses Python, Streamlit, pandas, pickle, and the TMDB API to recommend movies and display their posters.

Technologies Used:

Streamlit: For the interactive interface.
pandas: For data handling.
pickle: To load pre-trained movie data and similarity matrices.
requests: To fetch movie details and posters from the TMDB API.
How It Works:

Select a movie from the dropdown.
The system calculates the most similar movies using a pre-trained similarity matrix.
Recommended movie names and their posters are displayed.
Project Files: Due to the size of the files, the project is available for download from Google Drive:
Download the project here OR https://drive.google.com/drive/folders/14wAILzkZ2ui48EvMmOJ2nCpsiIt_-TNx?dmr=1&ec=wgc-drive-hero-goto

Setup Instructions:

Clone the repository:
git clone https://github.com/AnmolKumarSingh7/movie-recommender-system

Install the required libraries:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run app.py

Select a movie to get recommendations.

Note: You will need to replace the TMDB API key in the code to fetch movie posters.

License: Open-source under the MIT License.
