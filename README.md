# Movie Recommendation System 
A content-based Movie Recommendation System that suggests similar movies based on user input using TF-IDF vectorization and Cosine Similarity.
The project includes a Streamlit web interface where users can select a movie and receive top recommendations with plots and posters fetched via OMDB API.

# Features
-  Search any movie and get top similar recommendations  
-  NLP-based recommendation using **TF-IDF + Cosine Similarity**
-  Built with an intuitive **Streamlit web interface**
-  Auto-fetches movie posters & details using **OMDB API**
-  Fast computation using pre-saved ML pipeline

 # Tech Stack
| Category | Tools / Libraries |
|---------|--------------------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| NLP | NLTK |
| Vectorization | TF-IDF |
| Similarity | Cosine Similarity |
| Web Framework | Streamlit |
| API | OMDB API |
| Serialization | Joblib |
| IDE | VS Code |

# Movie Recommendation System
│── main.py                # Streamlit web app
│── recommend.py           # Recommendation logic
│── preprocess.py          # Data cleaning + NLP + TF-IDF
│── omdb_utils.py          # Fetch movie posters using OMDB API
│── config.json            # API key & paths
│── requirements.txt       # Dependencies
│── README.md              # Project documentation


