# 🎬 Movie Recommendation System

**This Movie Recommendation System** is a Gradio-based web app that recommends movies based on **content-based filtering** and **collaborative filtering**.  
This tool helps you discover similar movies by either using the movie's attributes (e.g., title, genre) or by analyzing user ratings and finding similarities between movies.

---

## 🌟 Features
- 🎥 **Movie Selection**: Choose a movie from a dropdown list.
- 🧠 **Content-Based Filtering**: Get recommendations based on movie attributes (e.g., title, genre).
- 🤝 **Collaborative Filtering**: Get recommendations based on user ratings and the similarity of movies rated by other users.
- 📊 **Cosine Similarity**: Uses cosine similarity to find movie similarities based on either content or user ratings.
- ⚡ Powered by **Scikit-learn** and **Gradio** for fast and accurate movie recommendations.
- 🎯 Simple Gradio interface for easy use.

---

## 🙋‍♀️ Usage
1. Select a movie from the dropdown list.
2. The system will recommend similar movies based on either **content-based filtering** or **collaborative filtering**.
3. View the movie recommendations in the following categories:
   - 🎬 **Content-Based Recommendations** (Based on movie title similarity)
   - 👥 **Collaborative Recommendations** (Based on user ratings and movie similarities)
4. Enjoy discovering new movies similar to your favorites!

---

## 💻 Setup

### Prerequisites
Ensure that you have the following installed:
- **Python 3.7+**
- **Pandas**: For data manipulation
- **NumPy**: For numerical operations
- **Scikit-learn**: For calculating cosine similarity
- **Gradio**: For building the web interface

To install the dependencies, run:

```bash
pip install pandas numpy scikit-learn gradio
