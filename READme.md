# 🎬 Movie Recommender System

This project is a **Content-Based Movie Recommendation System** built using Python.  
It recommends movies to users based on their similarity with other movies using textual metadata such as **genres, keywords, cast, and crew**.  

---

## 📌 Features
- Loads and processes the **TMDB 5000 Movies dataset**.  
- Performs **data cleaning and preprocessing** (handling missing values, extracting features).  
- Uses **NLP techniques** such as:
  - Tokenization  
  - Stemming  
  - Vectorization with **CountVectorizer**  
- Computes similarity between movies using **Cosine Similarity**.  
- Provides movie recommendations based on user input.  

---

## 📂 Dataset
The project uses the **[TMDB 5000 Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)** from Kaggle.  

- `tmdb_5000_movies.csv`  
- `tmdb_5000_credits.csv`  

---

## 🛠️ Technologies Used
- **Python**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Scikit-learn** – Machine learning utilities  
- **NLTK** – Natural Language Processing  
- **Pickle** – Model serialization  
- **Streamlit** – Web app deployment  

---

## 🚀 How It Works
1. **Data Preprocessing**  
   - Extracts genres, keywords, cast, and crew.  
   - Cleans and merges features into a single "tags" column.  

2. **Feature Engineering**  
   - Converts text data into vectors using CountVectorizer.  
   - Applies **Cosine Similarity** to find similar movies.  

3. **Recommendation Function**  
   - Input: Movie name  
   - Output: List of top 5 recommended movies.  

---

## ▶️ Installation & Usage

### 1. Clone this repository:
```bash
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
````

### 2. Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

### 3. Install dependencies:

```bash
pip install -r requirements.txt
```

### 📄 requirements.txt contains:

```
numpy
pandas
scikit-learn
nltk
streamlit
pickle5
```

### 4. Run the Jupyter Notebook:

```bash
jupyter notebook movie_recommender_system.ipynb
```

### 5. Or run the Streamlit app (if available):

```bash
streamlit run app.py
```

---

## 📊 Example

```python
recommend("Avatar")
```

**Output:**

```
1. Guardians of the Galaxy  
2. Star Wars: The Force Awakens  
3. Star Trek  
4. John Carter  
5. The Last Airbender  
```

---

## 📌 Future Improvements

* Deploy as a web app using **Streamlit / Flask**.
* Add **collaborative filtering** for hybrid recommendations.
* Integrate with **TMDB API** for real-time movie details & posters.

---

## 👨‍💻 Author

Developed by **Muhammad Hameed Ullah**

* 📧 Email: [dataanalyst8055@gmail.com](mailto:your.email@example.com)
* 🌐 Portfolio: \[https://github.com/Hameed8055]
