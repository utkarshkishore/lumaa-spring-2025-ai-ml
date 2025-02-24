# 🎬 Content-Based Movie Recommendation System

This project is a simple content-based movie recommendation system that suggests similar movies based on user input. It uses **TF-IDF vectorization** and **cosine similarity** to find the closest matches from a dataset of movie descriptions.

---

## 📂 **Dataset**

- The dataset used is a CSV file named `Top_Movies.csv`.
- It contains the following columns:
  - **Movie Name**: Title of the movie.
  - **Plot**: A short description or plot summary of the movie.

**Example Row:**
| Movie Name              | Plot                                                               |
|-------------------------|--------------------------------------------------------------------|
| Avengers: Endgame       | The Avengers assemble once more to reverse Thanos' actions.        |
| Interstellar            | A team travels through a wormhole in space to ensure humanity’s survival. |

---

## ⚙️ **Setup Instructions**

### ✅ **Requirements**

- Python 3.x
- Required libraries (install using pip):
  ```bash
  pip install pandas scikit-learn
