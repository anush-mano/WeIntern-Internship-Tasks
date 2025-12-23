📌 Task Description
Build a basic movie recommendation system using a TMDb‑style dataset that suggests similar movies based on their content.

Challenges

Implement content‑based filtering

Handle text similarity using TF‑IDF and cosine similarity

Display the top 5 movie recommendations based on user input

Optionally filter recommendations by genre

Make the system easy to run and understand in a Jupyter Notebook

Tech Stack
Python, Pandas, NumPy, Scikit‑learn, Matplotlib, Seaborn, WordCloud

🧠 Project Overview
In this notebook, a complete content‑based recommendation pipeline is implemented:

Loading and inspecting the movies dataset (≈4800 movies with 24 columns)

Selecting important text features: genres, keywords, tagline, cast, director

Handling missing values in these text columns

Combining selected features into a single text field for each movie

Converting text to numerical vectors using TF‑IDF

Computing movie‑to‑movie similarity using cosine similarity

Implementing a recommendation function that:

Accepts a movie title from the user

Uses fuzzy matching to handle small spelling mistakes

Returns the top 5 most similar movies, with an optional genre filter

The notebook also includes simple visualizations such as a word cloud and basic plots to understand the distribution of genres and text data.

🗂️ Files Included
movies.csv — Movies dataset containing title, genres, keywords, cast, director, etc.

movieRecommendation.ipynb — Jupyter Notebook with data loading, preprocessing, TF‑IDF, similarity calculation, and the interactive recommendation demo.

🚀 How to Run
bash
pip install pandas numpy scikit-learn matplotlib seaborn wordcloud
jupyter notebook movieRecommendation.ipynb
Then:

Open the notebook in your browser.

Run all cells from top to bottom.

When prompted, enter:

A movie title (e.g., Avengers)

An optional genre filter (or press Enter to skip)

View the top 5 recommended movies printed in the output.
