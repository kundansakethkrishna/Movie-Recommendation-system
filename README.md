 Movie Recommendation System

---

A Machine Learning-powered Movie Recommendation System that suggests movies based on user preferences and interests. The application uses content-based filtering techniques to analyze movie metadata and recommend similar movies through an interactive web interface.


🚀 Features

---

- 🎥 Movie Recommendation Engine – Recommends movies similar to the one selected by the user.
- 📊 Content-Based Filtering – Uses genres, keywords, cast, crew, and movie overviews to determine similarity.
- 🤖 Machine Learning Integration – Utilizes feature extraction and cosine similarity for accurate recommendations.
- 🔍 Movie Search Functionality – Allows users to search and select movies from the dataset.
- ⭐ Top Similar Movie Suggestions – Instantly displays relevant movie recommendations.
- 💻 Interactive Streamlit Interface – Clean and user-friendly web application.
- ⚡ Fast Processing – Uses a precomputed similarity matrix for quick recommendations.


🛠️ Tech Stack

---

Programming Language: Python 3.9+

Data Processing: Pandas, NumPy

Machine Learning: Scikit-learn

Recommendation Technique: Content-Based Filtering

Similarity Measure: Cosine Similarity

Web Framework: Streamlit

Dataset: Movie Metadata Dataset


📂 Project Structure

---

movie-recommendation-system/

├── app.py                 # Streamlit web application
├── recommender.py         # Recommendation engine logic
├── movies.csv             # Movie dataset
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation


⚙️ Installation & Setup

---

1. Clone the Repository

git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system

2. Install Dependencies

pip install -r requirements.txt

3. Run the Application

streamlit run app.py


🎯 How to Use

---

1. Launch the Streamlit application.
2. Select or search for a movie from the list.
3. Click the Recommend button.
4. View the recommended movies displayed on the screen.


🧠 How the Recommendation System Works

---

1. Movie metadata such as genres, keywords, cast, and overview are collected.
2. Relevant features are combined and converted into numerical vectors.
3. Cosine Similarity is used to measure similarity between movies.
4. The system finds and displays the most similar movies based on the selected movie.


📸 Output

---

The application allows users to select a movie and instantly receive recommendations for similar movies.


🚀 Future Scope

---

- Add movie posters and details using external APIs.
- Improve recommendations with hybrid filtering techniques.
- Deploy the application on cloud platforms.


📜 License

---

This project was developed for academic and educational purposes as part of a CRT Mini Project Submission.

Free to use and modify for learning purposes.
