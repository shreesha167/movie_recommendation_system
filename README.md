# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built using **Python**, **Pandas**, **Scikit-learn**, and **Natural Language Processing (NLP)** techniques. The system recommends movies similar to a selected movie by analyzing genres, keywords, cast, crew, and plot overview.

---

## 📌 Features

* Recommend similar movies based on content.
* Uses **Natural Language Processing (NLP)** for text preprocessing.
* Applies **Porter Stemming** to normalize words.
* Converts movie descriptions into numerical vectors using **CountVectorizer**.
* Calculates movie similarity using **Cosine Similarity**.
* Built using the **TMDB 5000 Movies Dataset**.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Jupyter Notebook

---

## 📂 Dataset

This project uses the following datasets:

* `tmdb_5000_movies.csv`
* `tmdb_5000_credits.csv`

The datasets contain information such as:

* Movie Title
* Overview
* Genres
* Keywords
* Cast
* Crew
* Movie ID

---

## 🚀 How It Works

1. Load the movie and credits datasets.
2. Merge both datasets using the movie title.
3. Select the required columns.
4. Handle missing values and remove duplicates.
5. Extract:

   * Genres
   * Keywords
   * Top 3 Cast Members
   * Director
6. Combine all extracted information into a single **tags** column.
7. Convert text to lowercase.
8. Apply **Porter Stemming** to reduce words to their root form.
9. Convert text into vectors using **CountVectorizer**.
10. Compute **Cosine Similarity** between movie vectors.
11. Recommend the top similar movies based on similarity scores.

---

## 📁 Project Structure

```text
Movie-Recommendation-System/
│
├── Movie Recommendation System.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── README.md
├── .gitignore
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/movie_recommendation_system.git
```

Navigate to the project folder:

```bash
cd movie_recommendation_system
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Movie Recommendation System.ipynb
```

---

## 📊 Machine Learning & NLP Concepts Used

* Content-Based Recommendation
* Data Preprocessing
* Feature Engineering
* Bag of Words (BoW)
* CountVectorizer
* Porter Stemming
* Cosine Similarity

---

## 📸 Example Recommendation

**Input:**

```text
Avatar
```

**Output:**

```text
Aliens
Guardians of the Galaxy
John Carter
Star Trek
Titan A.E.
```

*(Recommendations may vary depending on preprocessing and dataset version.)*

---

## 📚 Future Improvements

* Add a Streamlit web application.
* Display movie posters using the TMDB API.
* Add search suggestions with autocomplete.
* Improve recommendations using TF-IDF or Word2Vec.
* Deploy the application on Streamlit Cloud or Render.

---

## 👨‍💻 Author

**Shreesha Hegde**

GitHub: https://github.com/shreesha167

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
