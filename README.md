# 🎬 Content-Based Movie Recommendation System

This project is a simple content-based movie recommendation system that suggests similar movies based on user input. It uses **TF-IDF vectorization** and **cosine similarity** to find the closest matches from a dataset of movie descriptions.

---

## 📂 **Dataset**

- The dataset used is a CSV file named `Top_Movies.csv`.
- The link to the dataset is - https://www.kaggle.com/datasets/moazeldsokyx/the-500-best-movies-imdb?resource=download
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
- Clone this repo in your local machine.
- Run the .ipynb file and give input "I love action movies with superheroes and space battles."
- It will return the following output-
   🔥 Top 5 Movie Recommendations:

1. The Incredibles (Score: 0.2682)
   While trying to lead a quiet suburban life, a family of undercover superheroes are forced into action to save the world.

2. Gravity (Score: 0.1467)
   Two astronauts work together to survive after an accident leaves them stranded in space.

3. Gravity (Score: 0.1467)
   Two astronauts work together to survive after an accident leaves them stranded in space.

4. Spider-Man 2 (Score: 0.1359)
   Peter Parker is beset with troubles in his failing personal life as he battles a brilliant scientist named Doctor Otto Octavius.

5. Clerks (Score: 0.1299)
   A day in the lives of two convenience clerks named Dante and Randal as they annoy customers, discuss movies, and play hockey on the store roof.



---

## Dependecies used
- pandas
- scikit-learn
- numpy

### ✅ **Requirements**

- Python 3.x
- Required libraries (install using pip):
  ```bash
  pip install pandas scikit-learn numpy

### Salary Expectation**
- 20 to 30 USD per hour
  
