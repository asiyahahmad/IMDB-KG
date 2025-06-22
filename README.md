# IMDB-KG
IMDB-KG is a Python-based Knowledge Graph generator for movie data extracted from an IMDB dataset. The graph models movies and their attributes such as directors, actors, genres, production companies, year, duration, and ratings as interconnected nodes and edges. This allows for general analysis of relationships between entities in the movie domain.

# Getting Started
Prerequisites
- Python 3.7+
- pandas
- networkx
- matplotlib (for visualization)

Install required packages with:
pip install pandas networkx matplotlib

# Code Overview
The core function create_IMDB_KG(movie_data):

- Iterates over each movie record.
- Creates a movie node keyed by the movie title.
- Creates nodes for related entities (actors, director, genres, etc.).
- Creates shared attribute nodes for year, duration, votes, and average vote.
- Connects entities with labeled edges.

Dataset
The dataset used is sourced from this [IMDB Movie Dataset (CSV)](https://raw.githubusercontent.com/utkarshaditya01/IR---The-Entertainment-Knowledge-Graph/main/Code/final_dataset_imdb.csv), which contains movie metadata including title, cast, crew, genre, ratings, and more.

