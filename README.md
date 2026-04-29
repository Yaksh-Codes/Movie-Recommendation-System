# 🎬 Content-Based Movie Recommendation System

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-NLP-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green.svg)

## 📌 Project Overview
This project is a Machine Learning-based Movie Recommendation System. It suggests movies similar to the one a user searches for based on content features like genres, keywords, cast, and crew. By utilizing Natural Language Processing (NLP), the system extracts meaning from textual metadata to find the closest movie matches.

## ⚙️ Key Features
- **Data Preprocessing:** Merges and cleans the TMDB 5000 Movies & Credits datasets.
- **Feature Extraction:** Extracts top cast members, the director, genres, and keywords from complex JSON-like text strings.
- **NLP Vectorization:** Utilizes `CountVectorizer` to convert collapsed text tags into vectors (max_features=5000).
- **Similarity Scoring:** Calculates `cosine_similarity` across thousands of movies to generate the top 5 closest recommendations.
- **Model Serialization:** Exports the final data and similarity matrix using `pickle` for easy deployment.

## 🛠️ Tech Stack
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`, `ast`
- **Machine Learning / NLP:** `scikit-learn` (`CountVectorizer`, `cosine_similarity`)
- **Environment:** Jupyter Notebook

## 📂 Repository Structure
- `Code.ipynb` - Main Jupyter Notebook containing the data analysis, preprocessing, and modeling.
- `requirements.txt` - List of dependencies required to run the code.
- `README.md` - Project documentation.

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)[your-username]/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
