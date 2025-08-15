#  Movie Recommender System  

###  Project Overview  
This project is a **basic movie recommendation system** built using a **User-Based Collaborative Filtering** algorithm.  
The model analyzes user rating data to find patterns and predict user preferences.  

The goal is to **demonstrate a practical understanding** of core recommendation system principles using Python and data analysis libraries.  

---

###  Data Used  
The project uses the **MovieLens** dataset, specifically the `ratings_small.csv` file, which contains **100,000 movie ratings from 700 users**.  

**Dataset fields:**  
- **userId** — unique user identifier.  
- **movieId** — unique movie identifier.  
- **rating** — movie rating (from 0.5 to 5.0).  
- **timestamp** — time when the rating was given.  

---

###  Methodology  

1. **Data Preparation**  
   - Load and process `ratings_small.csv`.  
   - Transform the dataset into a **user–movie matrix**.  

2. **Similarity Calculation**  
   - Use **Cosine Similarity** to calculate similarity between all users based on their rating patterns.  

3. **Recommendation Generation**  
   - Identify a user's **nearest neighbors** (most similar users).  
   - Recommend movies that these neighbors have rated highly but the target user has not yet watched.  

---

###  Technologies Used  
- **Python** — main programming language.  
- **Pandas** — data manipulation and creation of the user–movie matrix.  
- **NumPy** — numerical operations.  
- **Scikit-learn** — calculation of user similarity via `cosine_similarity`.  

---

###  Author  
**Sergey Nikitin**  
