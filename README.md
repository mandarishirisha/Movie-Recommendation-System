MOVIE RECOMMENDATION SYSTEM

OVERVIEW

This project analyzes a dataset of movies and generates recommendations using content similarity.
It utilizes text vectorization (CountVectorizer or TF-IDF) and cosine similarity to find movies with similar metadata.

You can input a movie title, and the system returns a list of similar movies.

The project uses the TMDb 5000 Movie Dataset, which contains:




MOVIE TITLES

Cast and crew information

Genres

Keywords

Descriptions





Dataset source: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata



TECHNOLOGIES USED

Python 3

Pandas – for data cleaning and manipulation

NumPy – for numerical operations

Scikit-learn – for vectorization and similarity calculation

NLTK (optional) – for text preprocessing

Jupyter Notebook





HOW IT WORKS

1.Load and clean the dataset

2.Combine relevant features (genres, keywords, cast, crew, overview) into a single text field

3.Convert text data into numerical vectors using CountVectorizer

4.Compute cosine similarity between all movie vectors

5.Build a function to fetch top N similar movies given a movie name



INSTALLATION

1.Clone this repository:

git clone https://github.com/mandarishirisha/Movie-Recommendation-System.git



2.Navigate into the folder:

cd Movie-Recommendation-System


3.Install required libraries:

pip install -r requirements.txt



(If you don’t have a requirements.txt, you can install manually:)

pip install pandas numpy scikit-learn nltk



