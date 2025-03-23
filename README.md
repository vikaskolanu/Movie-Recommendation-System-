🎬 Movie Recommendation System

📚 Overview

The Movie Recommendation System leverages content-based and collaborative filtering techniques to suggest movies based on user input and preferences. Built using Python, this system dynamically identifies and displays similar movies through TF-IDF vectorization and cosine similarity.

🚀 Features

Search Bar with Live Results: Interactive search functionality using ipywidgets for real-time movie suggestions.

Content-Based Filtering: Uses TF-IDF Vectorizer to compute similarity between movie titles.

Collaborative Filtering: Recommends movies based on similar user preferences and ratings.

Dynamic Similarity Computation: Suggests top 5 most similar movies based on cosine similarity.

🔥 Technologies Used

Python for data processing and model implementation.

Pandas for data handling and manipulation.

Scikit-learn for vectorization and similarity computation.

Ipywidgets for building an interactive user interface.

📊 Dataset

The project uses:

movies.csv – Contains movie details such as movieId, title, and genres.

ratings.csv – Stores user ratings with columns userId, movieId, and rating.

You can download the dataset files from this link.

📝 How It Works

Preprocessing:

Cleans movie titles to remove special characters.

Converts movie titles to vectors using TF-IDF Vectorizer with bigram features.

Search & Recommendation:

Cosine similarity identifies top 5 similar movie titles based on user input.

Collaborative filtering recommends movies liked by similar users.

📡 Usage

Clone the repository:

   git clone https://github.com/your-username/movie-recommendation-system.git

Install required dependencies:

   pip install -r requirements.txt

Run the Jupyter Notebook:

   jupyter notebook movie_recommendations.ipynb

🧠 Future Enhancements

Integrate KNN for improved recommendations.

Build API for Flutter app integration.

Add model export using joblib or pickle.

🤝 Contributing

Feel free to fork the repository and submit pull requests for improvements or feature additions.
