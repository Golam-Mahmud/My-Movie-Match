# 🎬 Movie Recommendation System

## 📌 Project Overview
This project builds a **Movie Recommendation System** using TMDB ratings and IMDb's **weighted rating formula**. It incorporates both **content-based** and **collaborative filtering** techniques to provide personalized movie recommendations.

## 🚀 Features
- **Top Movies Chart**: Uses TMDB **Vote Count** and **Vote Averages** to generate ranked movie lists.
- **Content-Based Filtering**: Utilizes movie **overviews, taglines, cast, crew, genres, and keywords** for recommendations.
- **Collaborative Filtering**: Implements **Singular Value Decomposition (SVD)** via the Surprise Library for user-based recommendations.
- **Hybrid System**: Combines content-based and collaborative approaches for better recommendations.

## 📊 Methodology
1. **Dataset**: Movies and ratings are sourced from **TMDB (The Movie Database) API** and can be accessed from [Google Drive](https://drive.google.com/drive/folders/1kiVq_QiNg15m8MyhSVqlhPtoo3Ph8HcU).
2. **Weighted Rating Calculation**: Based on IMDb’s **formula** to rank movies.
3. **Content-Based Recommendation**:
   - One model uses **overviews & taglines**.
   - Another model utilizes **metadata (cast, crew, genre, keywords)**.
   - A filter prioritizes movies with **higher votes & better ratings**.
4. **Collaborative Filtering**:
   - Uses **Surprise Library** and **SVD algorithm**.
   - Achieved **RMSE < 1**.
   - Predicts **user-specific ratings** for movies.
5. **Hybrid Model**: Merges **content-based & collaborative filtering**.

## 🛠️ Installation
```bash
# Clone the repository
git clone <repository-url>
cd <repository-name>

## 🔥 Future Enhancements
- ✅ Add **deep learning** models (e.g., Autoencoders)
- ✅ Improve user-based recommendations
- ✅ Integrate real-time movie trending data

## 🤝 Contributing
Feel free to **fork** this repository, create a branch, and submit a **pull request**!

## 📜 License
This project is licensed under the **Creative Commons Zero v1.0 Universal**.
