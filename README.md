# 🎬 Movie Recommendation System

This project is a simple yet powerful **Movie Recommendation System** built using **Streamlit** for the UI, **Pandas & Pickle** for data handling, and **TMDb API** for fetching movie posters.  

## ✨ Features
- Search and select a movie from the dataset.  
- Get **top 5 movie recommendations** instantly.  
- Displays movie posters using **TMDb API**.  
- Interactive, user-friendly **Streamlit interface**.

## ⚙️ How It Works
1. User selects a movie from the dropdown list.  
2. The system checks the **cosine similarity matrix** to find the most similar movies.  
3. Top 5 movies are selected as recommendations.  
4. Posters for these movies are fetched using the **TMDb API**.  
5. Movies are displayed with **title + poster** in 5 columns. 

## 🛠️ Tech Stack
- **Frontend/UI** → Streamlit  
- **Backend** → Python  
- **Data Handling** → Pandas  
- **Model** → Cosine Similarity  
- **API** → TMDb API (for posters)   

## 🧠 Recommendation Logic

This project uses **Content-Based Filtering** with **Cosine Similarity**:

- Each movie is represented as a **vector** of features (title, genre, keywords, cast, crew).  
- Cosine Similarity = (A · B) / (||A|| ||B||) → measures similarity between two movie vectors.  
- For a given movie, the system finds the **top 5 most similar movies** using this metric.


