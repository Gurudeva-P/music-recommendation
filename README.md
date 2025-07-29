# 🎵 Music Recommendation System

This project is a content-based music recommendation system that suggests songs based on lyrical similarity. It uses Natural Language Processing (NLP) techniques and a similarity matrix trained on the **Million Song Dataset** (Lyrics subset).

---

## 📂 Project Structure

music-recommendation/
├── Model Training.ipynb # Jupyter Notebook for model training & similarity matrix generation
├── app.py # Streamlit app for user interaction
├── requirements.txt # Python dependencies
├── similarity.pkl # Precomputed similarity matrix (LFS)
├── spotify_millsongdata.csv # Lyrics dataset (LFS)
├── df.pkl # Preprocessed dataframe (LFS)
└── README.md

yaml
Copy code

---

## 🚀 Features

- Recommends songs based on lyrics
- Text vectorization using TF-IDF
- Cosine similarity-based ranking
- Interactive UI built with **Streamlit**

---

## 💻 How to Run

### 1. Clone the repository

````bash
git clone https://github.com/Gurudeva-P/music-recommendation.git
cd music-recommendation
2. Install dependencies
bash
Copy code
pip install -r requirements.txt
3. Download LFS files (first time only)
This project uses Git Large File Storage to manage .pkl and .csv files.

bash
Copy code
git lfs install
git lfs pull
4. Run the Streamlit app
bash
Copy code
streamlit run app.py
📈 Dataset
Dataset: Million Song Dataset (Lyric subset)

Format: .csv containing song titles, artist names, and lyrics

🧠 Model Info
Vectorizer: TF-IDF

Similarity: Cosine Similarity

Storage: Precomputed .pkl matrices for performance

📦 Dependencies
Python 3.8+

pandas

scikit-learn

nltk

streamlit

```bash
git clone https://github.com/your-username/music-recommender.git
cd music-recommender
pip install -r requirements.txt
streamlit run app.py
````
