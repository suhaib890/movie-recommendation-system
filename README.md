# 🎬 Movie Recommendation System

A **content-based movie recommendation system** built using Python, NLP, TF-IDF, and Cosine Similarity.

The system recommends movies similar to a movie selected by the user based on its **overview, genres, and tagline**.

## 🚀 Features

* Movie dataset preprocessing
* Duplicate and missing-value handling
* Genre extraction and transformation
* Text preprocessing using NLP
* Stopword removal
* Lemmatization
* TF-IDF vectorization
* Cosine similarity
* Top-N similar movie recommendations
* Model/data serialization using Pickle

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🧠 How It Works

The recommendation pipeline is:

```text
Movie Dataset
      ↓
Data Cleaning
      ↓
Overview + Genres + Tagline
      ↓
Text Preprocessing
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity
      ↓
Similar Movie Recommendations
```

## 🔍 NLP Processing

The text data is processed using:

1. Lowercasing
2. Punctuation removal
3. Tokenization
4. Stopword removal
5. Lemmatization

The processed text is then converted into numerical features using **TF-IDF**.

## 📐 Recommendation Method

The system uses **Cosine Similarity** to measure the similarity between movies.

When a movie title is provided, the system:

1. Finds the selected movie.
2. Gets its TF-IDF representation.
3. Calculates similarity with other movies.
4. Sorts movies by similarity score.
5. Returns the top recommended movies.

## 💻 Example

```python
recommend("Group Sex", 10)
```

The function returns the top 10 movies that are most similar to the selected movie.

## 📂 Project Files

```text
movie-recommendation-system/
│
├── Movie_Recommendation_System.ipynb
├── README.md
├── movies_metadata.csv
├── tfidf.pkl
├── tfidf_matrix.pkl
├── indices.pkl
└── df.pkl
```

## 📌 Project Type

**Machine Learning | NLP | Recommendation System**

## 🎯 Future Improvements

* Build a Streamlit web interface
* Add movie posters
* Add movie ratings and popularity
* Improve recommendation quality
* Deploy the application
* Add hybrid recommendation techniques
* Create an API using FastAPI

## 👨‍💻 Author

**Suhaib Ashraf**

Aspiring Data Analyst & Machine Learning Engineer
