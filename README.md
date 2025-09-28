# 🎧 Song Recommendation System

A music recommendation engine that suggests new tracks based on your existing playlist or favorite songs, leveraging the Million Playlist Dataset.

---

## 🔍 Project Overview

This repo aims to:

- Analyze and preprocess the Million Playlist Dataset (MPD)
- Extract relevant features from songs and playlists
- Build models that compute similarity or preference scores
- Provide song recommendations given an input (song or playlist)

---

## 📂 Structure

| Folder / File | Purpose |
|---|---|
| `Preprocessing.ipynb` | Data cleaning, normalization, feature extraction |
| `Modeling.ipynb` | Training models / recommendation logic |
| `Reading1M_feature_extraction.ipynb` | Experiments on extracting meaningful features from MPD |
| `Streamlit/` | (Optional) UI code to demo live recommendations |
| `README.md` | This file |

---

## 📦 Data

- The dataset used: **Million Playlist Dataset (MPD)**  
- Contains ~1 million playlists, with metadata (playlist name, number of songs, artists, duration etc.) :contentReference[oaicite:0]{index=0}  
- Source / more info: [AIcrowd – Million Playlist Dataset](https://www.aicrowd.com) :contentReference[oaicite:1]{index=1}  
- Inspired by projects such as [abdelrhmanelruby’s Spotify Recommendation System] :contentReference[oaicite:2]{index=2}

---

## 🔧 Approach & Methods

- Feature engineering on tracks & playlists (e.g. embedding, co-occurrence, metadata similarities)
- Similarity metrics (cosine distance, collaborative filtering, hybrid methods)
- Model evaluation (precision, recall, top-k recommendation performance)

---

## 🚀 Future Ideas & Extensions

- Integrate with Spotify / YouTube API for real streaming recommender
- Use deep learning embeddings (e.g. audio features with CNNs)
- Personalization: user profiles, taste drift over time
- Real-time recommendation system with latency constraints
- UI improvement: better visualization, feedback loop

---

## 🧾 Credits & References

- Project structure and baseline inspired by [abdelrhmanelruby / Spotify-Recommendation-System] :contentReference[oaicite:3]{index=3}  
- Dataset: Million Playlist Dataset (MPD)  
- Thanks to any open-source lib authors used (Scikit-learn, Pandas, etc.)

---
