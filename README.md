# 🎯 Recommendation Systems Portfolio

This repository is a **professional portfolio** containing selected **Recommendation System projects**.  
Each project demonstrates practical implementation of recommender system techniques on real-world datasets.

---

## 📂 Projects

### 🎬 FilmFinder: Content-Based Movie Recommender
**Category:** Recommendation Systems (Content-Based Filtering)

A content-based recommendation system that suggests movies based on similarity between item features such as genres, ..., descriptions and actors.

**Key Highlights:**
- Feature extraction from movie metadata
- Similarity computation using vector space models
- Personalized movie recommendations based on content similarity

**Techniques Used:**
- TF-IDF
- Cosine similarity
- Content-based filtering logic

📓 **Notebook**
```
FilmFinder/content_based_movie_recommender.ipynb
```

---

### 🎬 CineFusion: Hybrid Movie Recommendation System
**Category:** Hybrid Recommendation System (UBCF + IBCF)

A hybrid movie recommendation system that combines **User-Based Collaborative Filtering (UBCF)** and **Item-Based Collaborative Filtering (IBCF)** to provide personalized movie recommendations based on user behavior and item similarity.

**Key Highlights:**
- User–user similarity analysis for preference-based recommendations
- Item–item similarity analysis for content-agnostic recommendations
- Hybrid strategy combining UBCF and IBCF outputs
- Personalized recommendations based on collaborative patterns

**Techniques Used:**
- User-Based Collaborative Filtering (UBCF)
- Item-Based Collaborative Filtering (IBCF)
- Similarity computation using cosine similarity
- Hybrid recommendation strategy

```
CineFusion/ubcf_ibcf_hybrid_movie_recommender.ipynb
```

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- SciPy
- spaCy
- Jupyter Notebook

---

⭐ If you find this repository useful, feel free to give it a star.
