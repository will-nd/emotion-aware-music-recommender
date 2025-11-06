# 🎧 Emotion-Aware Music Recommendation System

### MSc Computer Science Final Project

This project develops an **emotion-aware music recommendation system** that suggests songs based on the listener’s emotional state, inferred directly from audio features.

By combining **music emotion recognition (MER)** techniques with a **content-based recommendation approach**, the system predicts the emotional characteristics of songs — measured through *valence* (positivity/negativity) and *arousal* (energy/intensity) — and recommends tracks whose emotional profiles best match or complement a user’s mood.

---

## 🔍 Project Overview

### 🎯 Objective
To design and evaluate a music recommendation system that predicts and leverages song emotions derived from audio features to enhance user experience in mood-based music discovery.

### 🧠 Methodology
1. **Data Collection** – Use publicly available emotion-annotated music datasets (e.g., DEAM) and Spotify’s audio feature API.  
2. **Feature Extraction** – Extract spectral, rhythmic, and timbral features using `librosa` and merge with Spotify metadata.  
3. **Emotion Prediction** – Train regression models to predict *valence* and *arousal* scores from extracted features.  
4. **Recommendation** – Recommend songs closest to the user’s input mood in the valence–arousal space.  
5. **Evaluation** – Assess model accuracy (RMSE, correlation) and recommendation quality through user feedback.

---

## 🧩 Tech Stack
- **Python** – Core development  
- **Librosa** – Audio feature extraction  
- **Scikit-learn** – Machine learning models  
- **Spotify API (Spotipy)** – Song metadata and features  
- **Pandas / NumPy** – Data processing  
- **Matplotlib / Seaborn** – Visualisation and analysis  
- **Jupyter Notebook** – Experimentation environment  

---

## 📂 Project Structure
