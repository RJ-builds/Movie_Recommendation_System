# 🎬 Movie Recommendation System

A simple **content-based movie recommendation system** built with Python and Machine Learning.

Ever watched a movie and immediately wanted to find something similar?

This project explores how a machine can make that kind of recommendation by understanding the **textual descriptions of movies** and finding other movies with similar content.

---

## 📌 About the Project

The goal of this project is to build a basic recommendation system without manually creating rules such as:

> "If you liked Interstellar, you should watch The Martian."

Instead, the system looks at the descriptions of the movies, converts the text into numerical representations, and calculates how similar the movies are to each other.

For this project, I used a **content-based filtering approach**.

The recommendation is based on the **content of the movie**, not on user ratings or the behaviour of other users.

---

## 🔄 How It Works

The complete workflow is:

```text
Movie Descriptions
        ↓
   TF-IDF Vectorization
        ↓
Numerical Representation
        ↓
   Cosine Similarity
        ↓
Find Similar Movies
        ↓
     Recommendations
