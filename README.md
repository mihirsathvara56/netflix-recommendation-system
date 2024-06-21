# Netflix Recommendation System

This is a Python-based Netflix recommendation system that uses TF-IDF and cosine similarity to recommend movies based on genres.

## Features
- Cleans and preprocesses data.
- Uses TF-IDF vectorization for text data.
- Calculates cosine similarity between movies.
- Recommends movies based on a given title.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/netflix-recommendation-system.git
    cd netflix-recommendation-system
    ```

2. Install the required libraries:
    ```bash
    pip install numpy pandas scikit-learn nltk
    ```

3. Download NLTK stopwords:
    ```python
    import nltk
    nltk.download('stopwords')
    ```

## Usage

1. Ensure the dataset `netflixData.csv` is in the project directory.

2. Run the Python script:
    ```bash
    python netflix_recommendation.py
    ```

3. The script will print a list of recommended movie titles based on the given title.

## Project Structure

```plaintext
├── netflix_recommendation.py
├── netflixData.csv
├── README.md
└── .gitignore
