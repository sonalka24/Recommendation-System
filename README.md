# Recommendation System

## 📌 Overview
This project implements a **Movie Recommendation System** using collaborative filtering techniques. It leverages user ratings and movie metadata to suggest movies that users are likely to enjoy.

The system is built using Python and Jupyter Notebook, and it uses datasets containing movie details and user ratings.

---

## 📂 Project Structure
---

## 📊 Datasets
- **movies.csv**  
  Contains metadata about movies:
  - `movieId`: Unique identifier for each movie
  - `title`: Movie title
  - `genres`: Genres associated with the movie

- **ratings.csv**  
  Contains user ratings:
  - `userId`: Unique identifier for each user
  - `movieId`: ID of the movie rated
  - `rating`: Rating given by the user (typically 0.5 to 5.0)
  - `timestamp`: When the rating was given

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Scikit-learn** for similarity calculations
- **Jupyter Notebook** for interactive development

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd Recommendation-System

pip install pandas numpy scikit-learn

jupyter notebook "Recommender System.ipynb"