readme_text = """
# 🎬 Movie Recommendation System using KNN

This project is a simple movie recommendation system built using Python, pandas, and the K-Nearest Neighbors (KNN) algorithm. It utilizes the popular MovieLens dataset to recommend movies similar to the ones a user has rated highly.

## 📂 Dataset
- **ratings.csv** — Contains user ratings for movies.
- **movies.csv** — Contains movie titles and metadata.

## 💡 Key Features
- Collaborative Filtering using KNN.
- Cosine similarity to find similar movies.
- Sparse Matrix representation for memory efficiency.
- Recommends top-k similar movies based on a user’s favorite.

## 🔧 Technologies Used
- Python
- pandas, NumPy
- scikit-learn
- scipy (CSR Matrix)
- Google Colab (for execution)

## 🚀 How to Run
1. Upload `ratings.csv` and `movies.csv` in your Colab environment.
2. Run all the code cells in order.
3. Call `recommend_movies_for_user(user_id, X, ...)` with a valid user ID to get recommendations.

## 📌 Sample Output

## 📈 Future Improvements
- Add support for content-based filtering.
- Deploy as a Flask API or Streamlit app.
- Allow user login and dynamic rating submission.

## 🧑‍💻 Author
- **K Srikar Reddy**
- 📧 khambalapuramsrikar@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/srikar-reddy-3b101135b)
