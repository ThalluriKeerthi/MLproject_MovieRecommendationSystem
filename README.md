# 🎬 Movie Recommendation System using Machine Learning

A content-based Movie Recommendation System built with Python and Machine Learning that suggests movies similar to a user's favorite movie. The system uses **TF-IDF Vectorization** and **Cosine Similarity** to find and recommend movies based on their genres, keywords, cast, director, and tagline.

## 🚀 Features

* Movie recommendations based on user input.
* Content-based filtering approach.
* Uses movie metadata such as:

  * Genres
  * Keywords
  * Tagline
  * Cast
  * Director
* Handles spelling mistakes using fuzzy string matching.
* Recommends the top similar movies instantly.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity
* Difflib

## 📂 Dataset

The project uses a movie dataset (`movies.csv`) containing:

* Title
* Genres
* Keywords
* Tagline
* Cast
* Director

## ⚙️ How It Works

1. Load and preprocess the movie dataset.
2. Select important features:

   * Genres
   * Keywords
   * Tagline
   * Cast
   * Director
3. Combine all selected features into a single text column.
4. Convert text data into numerical vectors using TF-IDF.
5. Calculate similarity scores using Cosine Similarity.
6. Accept a movie name from the user.
7. Find the closest matching movie title.
8. Recommend the most similar movies based on similarity scores.

## 📸 Example

### Input

```text
Enter your favourite movie name: Avatar
```

### Output

```text
Movies suggested for you:

1. Guardians of the Galaxy
2. Star Trek
3. John Carter
4. Alien
5. Star Wars
```

## 📁 Project Structure

```text
Movie-Recommendation-System/
│
├── movies.csv
├── Movie_Recommendation_System_using_Machine_Learning.ipynb
├── README.md
└── requirements.txt
```

## ▶️ Installation

### Clone the repository

```bash
git clone <your-repository-url>
```

### Install dependencies

```bash
pip install numpy pandas scikit-learn
```

### Run the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Movie_Recommendation_System_using_Machine_Learning.ipynb
```

## 🔮 Future Improvements

* Add collaborative filtering.
* Build a web application using Flask or Streamlit.
* Integrate movie posters and ratings.
* Deploy the project online.
* Improve recommendation accuracy using hybrid models.

## 👨‍💻 Author

**Keerthi Thalluri**

⭐ If you found this project useful, consider giving it a star on GitHub!
